code snippets back-up
```
#warning 测试代码
#ifdef DEBUG
<#code here#>
#else// release执行：
<#code here#>
#endif

#pragma mark - <#code here#>

    dispatch_async(dispatch_get_global_queue(0, 0), ^{
        <#code here#>
    });
        
    dispatch_async(dispatch_get_main_queue(), ^{
        <#code here#>
    });
    
    dispatch_after(dispatch_time(DISPATCH_TIME_NOW, (int64_t)(<#time#> * NSEC_PER_SEC)), dispatch_get_main_queue(), ^{
        <#code here#>
    });
    
    if (@available(iOS <#system version#>, *)) {
        <#code here#>
    }

    @property (nonatomic, weak) id <<#delegate#>> delegate;
    if (self.delegate && [self.delegate respondsToSelector:@selector(<#SEL NAME#>)]) {
        [self.delegate <#SEL NAME#>];
    }

@property (nonatomic, <#key#>) <#type#> *<#name#>;
```
