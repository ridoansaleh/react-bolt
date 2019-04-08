```
{
    test: /\.eot(\?v=\d+\.\d+\.\d+)?$/,
    exclude: /node_modules/,
    loader: 'file-loader'
}
```

Keterangan  
1. /words/ : tanda slash adalah menunjukkan RegExp. `words` disebut dengan istilah "pattern". 
2. `\.` : ??? 
3. `\?` : ??
4. `\d+` : setidaknya terdapat 1 angka
