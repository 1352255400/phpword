# phpword

require 'WordHelper.php';


$data = array();
$data['file_name'] = 'word名称';//文件名
$data['content'] = 'word内容';//导出内容

$word = new WordHelper();
$word->index($data);
