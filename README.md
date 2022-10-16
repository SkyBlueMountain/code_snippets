# code_snippets


### plotly histogram with split
```
# hi hi
## hello hello
fig = px.histogram(data,  x = "coupon", color='Y', text_auto = True)
fig
```
<img src="/image/bar_split.png">

```
df['newColumnName'] = df.column1.apply(lambda x: 'newString' if 'stringContains' in x.lower() else x)
```
