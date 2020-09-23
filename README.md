<div align="center">

## bin2dec


</div>

### Description

binary to decimal convertion
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Rubin](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/rubin.md)
**Level**          |Beginner
**User Rating**    |5.0 (15 globes from 3 users)
**Compatibility**  |C\+\+ \(general\)
**Category**       |[Algorithms](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/algorithms__3-29.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/rubin-bin2dec__3-3763/archive/master.zip)





### Source Code

```
#include <iostream.h>
#include <string.h>
int main()
{
	char *binary="111"; //this is 7 dec.
	int decimal=0;
		for (int i=0; i<strlen(binary); ++i)
	{
		decimal=decimal*2+(binary[i]=='1'?1:0);
	}
	cout << decimal <<endl;
	return 0;
	//improvement on previous code
}
```

