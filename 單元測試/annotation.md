# Junit 4

## Annotation

* @Before
  在每一個@test前先執行
* @After
  在每一個@test後再執行
* @BeforeClass
  在執行class前先執行
* @AfterClass
  在執行完class後執行
* @Ignore
  忽略該測試

## Assertion
 * assertEquals 驗證2個物件是否相等
 * assertNotEquals 驗證2個物件是否不相等
 * assertTrue 驗證是否為真
 * assertFalse 驗證是否為非
 * assertNull 驗證物件是否為null
 * assertNotNull 驗證物件是否不為null
 * assertArrayEquals 驗證陣列是否相同
 #### 使用情境: 
    1. 比對兩個物件是否相同時，應使用AssertEqual而非AssertTrue
    2. 若比對內容為布林值，使用AsstTrue,而非AssertEqual
    3. 不要使用反向的寫法，錯吳範例： assertFalse(!condition)
    4. 預期為null時，使用AssertNull，而非AssertEqual
