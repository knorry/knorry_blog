函数里有函数定义
===============

这样只能调用一次

`function aa(){
	function bb(){
		echo "asdfas\n";
		cc();
		// function  dd(){
		echo "dddd";
		}
	}
		function cc(){
			echo "ccc\n";
		}

	for ($i=0; $i < 4; $i++) { 
		bb();
		cc();
	}
}

aa();
aa();`

1. test
2. test2
3. test3
