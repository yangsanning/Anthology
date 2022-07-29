### EditText动态InputType属性

editText.setInputType(InputType.TYPE_NULL)
| 方法 | 说明 |
| --- | --- |
| InputType.TYPE_NULL | 输入类型为没有指定明确的类型的特殊内容类型 |
| InputType.TYPE_CLASS_TEXT | 输入类型为普通文本 |
| InputType.TYPE_CLASS_NUMBER | 输入类型为数字文本 |
| InputType.TYPE_CLASS_PHONE | 输入类型为电话号码 |
| InputType.TYPE_CLASS_DATETIME | 输入类型为日期和时间 |
| InputType.TYPE_DATETIME_VARIATION_NORMAL | 输入类型为{@link#TYPE_CLASS_DATETIME}的缺省变化值，允许输入日期和时间 |
| InputType.TYPE_DATETIME_VARIATION_DATE | 输入类型为{@link#TYPE_CLASS_DATETIME}的缺省变化值，只允许输入一个日期 |
| InputType.TYPE_DATETIME_VARIATION_TIME |  |
| InputType.TYPE_CLASS_DATETIME | 输入类型为{@link#TYPE_CLASS_DATETIME}的缺省变化值，只允许输入一个时间 |
| InputType.TYPE_MASK_CLASS | 输入类型为决定所给文本整体类的位掩码 |
| InputType.TYPE_MASK_FLAGS | 输入类型为提供附加标志位选项的位掩码 |
| InputType.TYPE_MASK_VARIATION | 输入类型为决定基类内容变化的位掩码 |
| InputType.TYPE_NUMBER_FLAG_DECIMAL | 输入类型为小数数字，允许十进制小数点提供分数值 |
| InputType.TYPE_NUMBER_FLAG_SIGNED | 输入类型为数字是带符号的，允许在开头带正号或者负号 |
| InputType.TYPE_NUMBER_VARIATION_NORMAL | 输入类型为{@link#TYPE_CLASS_NUMBER}的缺省变化值：为纯普通数字文本 |
| InputType.TYPE_NUMBER_VARIATION_PASSWORD | 输入类型为{@link#TYPE_CLASS_NUMBER}的缺省变化值：为数字密码 |
| InputType.TYPE_TEXT_FLAG_AUTO_COMPLETE | 输入类型为自动完成文本类型 |
| InputType.TYPE_TEXT_FLAG_AUTO_CORRECT | 输入类型为自动纠正文本类型 |
| InputType.TYPE_TEXT_FLAG_CAP_CHARACTERS | 输入类型为所有字符大写 |
| InputType.TYPE_TEXT_FLAG_CAP_SENTENCES | 输入类型为每句的第一个字符大写 |
| InputType.TYPE_TEXT_FLAG_CAP_WORDS | 哈哈 |
| InputType.TYPE_MASK_FLAGS | 输入类型为每个单词的第一个字母大写 |
| InputType.TYPE_TEXT_FLAG_IME_MULTI_LINE | 输入多行文本 |
| InputType.TYPE_TEXT_FLAG_NO_SUGGESTIONS | 进行输入时，输入法无提示 |
| InputType.TYPE_TEXT_VARIATION_SHORT_MESSAGE | 输入一个短的，可能是非正式的消息，如即时消息或短信 |
| InputType.TYPE_TEXT_VARIATION_LONG_MESSAGE | 输入长内容，可能是正式的消息内容，比如电子邮件的主体 |
| InputType.TYPE_TEXT_VARIATION_FILTER | 输入文本以过滤列表等内容 |
| InputType.TYPE_TEXT_VARIATION_EMAIL_ADDRESS | 输入一个电子邮件地址 |
| InputType.TYPE_TEXT_VARIATION_EMAIL_SUBJECT | 输入电子邮件主题行 |
| InputType.TYPE_TEXT_VARIATION_PASSWORD | 输入一个密码 |
| InputType.TYPE_TEXT_VARIATION_NORMAL | 输入老式的普通文本 |
| InputType.TYPE_TEXT_VARIATION_PERSON_NAME | 输入人名 |
| InputType.TYPE_TEXT_VARIATION_POSTAL_ADDRESS | 输入邮寄地址 |
| InputType.TYPE_TEXT_VARIATION_PHONETIC | 输入语音发音输入文本，如联系人拼音名称字段 |
| InputType.TYPE_TEXT_VARIATION_URI | 输入对用户可见的密码 |
| InputType.TYPE_TEXT_VARIATION_VISIBLE_PASSWORD | 输入URI |
| InputType.TYPE_TEXT_VARIATION_WEB_EDIT_TEXT | 输入网页表单中的文本 |
| InputType.TYPE_TEXT_VARIATION_WEB_EMAIL_ADDRESS输入网页表单中的邮件地址 |  |
| InputType.TYPE_TEXT_VARIATION_WEB_PASSWORD | 输入网页表单中的密码 |
