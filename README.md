templates-vim
=============

vim plugin and template

Description:
vim下的插件和模板。
仅仅是为了个人方便，当然对你也有帮助，那是我的荣幸。
以下称为次工程为project.

该project主要包含[3]个目录，
plugin/
  template_load.vim
doc/
templates/
  tpl.c

创建plugin/template_load.vim文件，该文件的主要作用是根据
templates/目录下的模板文件来创建模板。
该文件copy于网上，里面的内容可以自由修改，但请保留原作者
信息。THX!

创建templates/tpl.c文件，改文件为*.c文件的模板，当创建
一个新的.c文件时就会出现下面的模板：
--------------
/*
    * Author: Qiao Zhao <qiaozqjhsy@gmail.com>
	 * Website: www.linuxqiao.org
	  *
	   * File: test.c
	    * Create Date: 2013-02-16 23:01:25
		 */

#include <stdio.h>

int main(int argc, char *argv[])
{

	    return 0;
}
---------------

reference:
http://www.vim.org/scripts/script.php?script_id=2834
