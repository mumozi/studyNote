# 字符串及数组操作函数



```php
addcslashes()  返回在指定的字符前添加反斜杠的字符串。
addslashes()   返回在预定义的字符前添加反斜杠的字符串。
bin2hex()  把 ASCII 字符的字符串转换为十六进制值。
chop() 移除字符串右侧的空白字符或其他字符。
chr()  从指定 ASCII 值返回字符。
chunk_split()  把字符串分割为一连串更小的部分。
convert_cyr_string()   把字符串由一种 Cyrillic 字符集转换成另一种。
convert_uudecode() 对 uuencode 编码的字符串进行解码。
convert_uuencode() 使用 uuencode 算法对字符串进行编码。
count_chars()  返回字符串所用字符的信息。
crc32()    计算一个字符串的 32 位 CRC（循环冗余校验）。
crypt()    单向的字符串加密法（hashing）。
echo() 输出一个或多个字符串。
explode()  把字符串打散为数组。
fprintf()  把格式化的字符串写入到指定的输出流。
get_html_translation_table()   返回 htmlspecialchars() 和 htmlentities() 使用的翻译表。
hebrev()   把希伯来（Hebrew）文本转换为可见文本。
hebrevc()  把希伯来（Hebrew）文本转换为可见文本，并把新行（\n）转换为 <br>。
hex2bin()  把十六进制值的字符串转换为 ASCII 字符。
html_entity_decode()   把 HTML 实体转换为字符。
htmlentities() 把字符转换为 HTML 实体。
htmlspecialchars_decode()  把一些预定义的 HTML 实体转换为字符。
htmlspecialchars() 把一些预定义的字符转换为 HTML 实体。
implode()  返回一个由数组元素组合成的字符串。
join() implode() 的别名。
lcfirst()  把字符串中的首字符转换为小写。
levenshtein()  返回两个字符串之间的 Levenshtein 距离。
localeconv()   返回本地数字及货币格式信息。
ltrim()    移除字符串左侧的空白字符或其他字符。
md5()  计算字符串的 MD5 散列。
md5_file() 计算文件的 MD5 散列。
metaphone()    计算字符串的 metaphone 键。
money_format() 返回格式化为货币字符串的字符串。
nl_langinfo()  返回指定的本地信息。
nl2br()    在字符串中的每个新行之前插入 HTML 换行符。
number_format()    通过千位分组来格式化数字。
ord()  返回字符串中第一个字符的 ASCII 值。
parse_str()    把查询字符串解析到变量中。
print()    输出一个或多个字符串。
printf()   输出格式化的字符串。
quoted_printable_decode()  把 quoted-printable 字符串转换为 8 位字符串。
quoted_printable_encode()  把 8 位字符串转换为 quoted-printable 字符串。
quotemeta()    引用元字符。
rtrim()    移除字符串右侧的空白字符或其他字符。
setlocale()    设置地区信息（地域信息）。
sha1() 计算字符串的 SHA-1 散列。
sha1_file()    计算文件的 SHA-1 散列。
similar_text() 计算两个字符串的相似度。
soundex()  计算字符串的 soundex 键。
sprintf()  把格式化的字符串写入一个变量中。
sscanf()   根据指定的格式解析来自一个字符串的输入。
str_getcsv()   把 CSV 字符串解析到数组中。
str_ireplace() 替换字符串中的一些字符（大小写不敏感）。
str_pad()  把字符串填充为新的长度。
str_repeat()   把字符串重复指定的次数。
str_replace()  替换字符串中的一些字符（大小写敏感）。
str_rot13()    对字符串执行 ROT13 编码。
str_shuffle()  随机地打乱字符串中的所有字符。
str_split()    把字符串分割到数组中。
str_word_count()   计算字符串中的单词数。
strcasecmp()   比较两个字符串（大小写不敏感）。
strchr()   查找字符串在另一字符串中的第一次出现。（strstr() 的别名。）
strcmp()   比较两个字符串（大小写敏感）。
strcoll()  比较两个字符串（根据本地设置）。
strcspn()  返回在找到任何指定的字符之前，在字符串查找的字符数。
strip_tags()   剥去字符串中的 HTML 和 PHP 标签。
stripcslashes()    删除由 addcslashes() 函数添加的反斜杠。
stripslashes() 删除由 addslashes() 函数添加的反斜杠。
stripos()  返回字符串在另一字符串中第一次出现的位置（大小写不敏感）。
stristr()  查找字符串在另一字符串中第一次出现的位置（大小写不敏感）。
strlen()   返回字符串的长度。中文字符串的处理使用 mb_strlen() 函数。
strnatcasecmp()    使用一种"自然排序"算法来比较两个字符串（大小写不敏感）。
strnatcmp()    使用一种"自然排序"算法来比较两个字符串（大小写敏感）。
strncasecmp()  前 n 个字符的字符串比较（大小写不敏感）。
strncmp()  前 n 个字符的字符串比较（大小写敏感）。
strpbrk()  在字符串中搜索指定字符中的任意一个。
strpos()   返回字符串在另一字符串中第一次出现的位置（大小写敏感）。
strrchr()  查找字符串在另一个字符串中最后一次出现。
strrev()   反转字符串。
strripos() 查找字符串在另一字符串中最后一次出现的位置(大小写不敏感)。
strrpos()  查找字符串在另一字符串中最后一次出现的位置(大小写敏感)。
strspn()   返回在字符串中包含的特定字符的数目。
strstr()   查找字符串在另一字符串中的第一次出现（大小写敏感）。
strtok()   把字符串分割为更小的字符串。
strtolower()   把字符串转换为小写字母。
strtoupper()   把字符串转换为大写字母。
strtr()    转换字符串中特定的字符。
substr()   返回字符串的一部分。
mb_substr()    返回中文字符串的一部分。
substr_compare()   从指定的开始位置（二进制安全和选择性区分大小写）比较两个字符串。
substr_count() 计算子串在字符串中出现的次数。
substr_replace()   把字符串的一部分替换为另一个字符串。
trim() 移除字符串两侧的空白字符和其他字符。
ucfirst()  把字符串中的首字符转换为大写。
ucwords()  把字符串中每个单词的首字符转换为大写。
vfprintf() 把格式化的字符串写到指定的输出流。
vprintf()  输出格式化的字符串。
vsprintf() 把格式化字符串写入变量中。
wordwrap() 按照指定长度对字符串进行折行处理。
```





```php
array()    创建数组。
array_change_key_case()    把数组中所有键更改为小写或大写。
array_chunk()  把一个数组分割为新的数组块。
array_column() 返回输入数组中某个单一列的值。
array_combine()    通过合并两个数组来创建一个新数组。
array_count_values()   用于统计数组中所有值出现的次数。
array_diff()   比较数组，返回差集（只比较键值）。
array_diff_assoc() 比较数组，返回差集（比较键名和键值）。
array_diff_key()   比较数组，返回差集（只比较键名）。
array_diff_uassoc()    比较数组，返回差集（比较键名和键值，使用用户自定义的键名比较函数）。
array_diff_ukey()  比较数组，返回差集（只比较键名，使用用户自定义的键名比较函数）。
array_fill()   用给定的键值填充数组。
array_fill_keys()  用指定键名的给定键值填充数组。
array_filter() 用回调函数过滤数组中的元素。
array_flip()   交换数组中的键和值。
array_intersect()  比较数组，返回交集（只比较键值）。
array_intersect_assoc()    比较数组，返回交集（比较键名和键值）。
array_intersect_key()  比较数组，返回交集（只比较键名）。
array_intersect_uassoc()   比较数组，返回交集（比较键名和键值，使用用户自定义的键名比较函数）。
array_intersect_ukey() 比较数组，返回交集（只比较键名，使用用户自定义的键名比较函数）。
array_key_exists() 检查指定的键名是否存在于数组中。
array_keys()   返回数组中所有的键名。
array_map()    把数组中的每个值发送到用户自定义函数，返回新的值。
array_merge()  把一个或多个数组合并为一个数组。
array_merge_recursive()    递归地合并一个或多个数组。
array_multisort()  对多个数组或多维数组进行排序。
array_pad()    用值将数组填补到指定长度。
array_pop()    删除数组的最后一个元素（出栈）。
array_product()    计算数组中所有值的乘积。
array_push()   将一个或多个元素插入数组的末尾（入栈）。
array_rand()   返回数组中一个或多个随机的键。
array_reduce() 通过使用用户自定义函数，以字符串返回数组。
array_replace()    使用后面数组的值替换第一个数组的值。
array_replace_recursive()  递归地使用后面数组的值替换第一个数组的值。
array_reverse()    以相反的顺序返回数组。
array_search() 搜索数组中给定的值并返回键名。
array_shift()  删除数组中首个元素，并返回被删除元素的值。
array_slice()  返回数组中被选定的部分。
array_splice() 删除并替换数组中指定的元素。
array_sum()    返回数组中值的和。
array_udiff()  比较数组，返回差集（只比较值，使用一个用户自定义的键名比较函数）。
array_udiff_assoc()    比较数组，返回差集（比较键和值，使用内建函数比较键名，使用用户自定义函数比较键值）。
array_udiff_uassoc()   比较数组，返回差集（比较键和值，使用两个用户自定义的键名比较函数）。
array_uintersect() 比较数组，返回交集（只比较值，使用一个用户自定义的键名比较函数）。
array_uintersect_assoc()   比较数组，返回交集（比较键和值，使用内建函数比较键名，使用用户自定义函数比较键值）。
array_uintersect_uassoc()  比较数组，返回交集（比较键和值，使用两个用户自定义的键名比较函数）。
array_unique() 删除数组中的重复值。
array_unshift()    在数组开头插入一个或多个元素。
array_values() 返回数组中所有的值。
array_walk()   对数组中的每个成员应用用户函数。
array_walk_recursive() 对数组中的每个成员递归地应用用户函数。
arsort()   对关联数组按照键值进行降序排序。
asort()    对关联数组按照键值进行升序排序。
compact()  创建包含变量名和它们的值的数组。
count()    返回数组中元素的数目。
current()  返回数组中的当前元素。
each() 返回数组中当前的键／值对。
end()  将数组的内部指针指向最后一个元素。
extract()  从数组中将变量导入到当前的符号表。
in_array() 检查数组中是否存在指定的值。
key()  从关联数组中取得键名。
krsort()   对数组按照键名逆向排序。
ksort()    对数组按照键名排序。
list() 把数组中的值赋给一些变量。
natcasesort()  用“自然排序”算法对数组进行不区分大小写字母的排序。
natsort()  用“自然排序”算法对数组排序。
next() 将数组中的内部指针向前移动一位。
pos()  current() 的别名。
prev() 将数组的内部指针倒回一位。
range()    创建包含指定范围单元的数组。
reset()    将数组的内部指针指向第一个元素。
rsort()    对数组逆向排序。
shuffle()  将数组打乱。
sizeof()   count() 的别名。
sort() 对数组排序。
uasort()   使用用户自定义的比较函数对数组中的键值进行排序。
uksort()   使用用户自定义的比较函数对数组中的键名进行排序。
usort()    使用用户自定义的比较函数对数组进行排序。
```

