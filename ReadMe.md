说明：后续软件编写代码统一采用Qt类型：

文档批注
    /*! \file myfile.h
        \brief 档案简易说明
    
        详细说明.
        
        \author 作者信息
    */


函数或者类批注
    /*！
     * @brief class或function的简易说明...
     *
     * class或function的详细说明...
     * ...
     */
	 
	 
	 
函数内部区块批注
	/*!
	 * ... text ...
	 */
	 
单行批注(用于批注注释前面这一行代码的意义)
	/*!< ... 批注 ... */
	
常用指令@？
@file    档案的批注说明。

@author  作者的信息

@brief	 用于class 或function的批注中，后面为class 或function的简易说明。

@param   格式为@param $arg_name 参数说明   主要用于函式说明中，后面接参数的名字，然后再接关于该参数的说明。

@return  后面接函数传回值的说明。用于function的批注中, 说明该函数的传回值。

@retval  格式为 @retval $value 传回值说明   主要用于函式说明中，说明特定传回值的意义。所以后面要先接一个传回值。然后在放该传回值的说明。

