## Install
```
python -m pip install git+https://github.com/wilianzilv/pandas-excel-view
```

## Usage
```py
import pandas_excel_view as pdv

pdv.show(df)
```


## Multiple Sheets
```py
pdv.show(df1, "lorem")

pdv.show(df2, "ipsum")
```

## Multiple Workbooks
```py
from pandas_excel_view import PandasExcelView

pdv0 = PandasExcelView()
pdv1 = PandasExcelView()
```



