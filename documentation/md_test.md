# MD_TEST


- [Constants](#constants)



- [MD_EXAMPLE Procedure](#md_example)





## Constants<a name="constants"></a>

Name | Code | Description
--- | --- | ---
procName | <pre>procName       Constant Varchar2(30) := 'md_test';</pre> | The Procedure Name
procVersion | <pre>procVersion    Constant Varchar2(30) := 'V01.00.00';</pre> | Version Number for the procedure






 
## MD_EXAMPLE Procedure<a name="md_example"></a>


<p>
<p>A Sample method to test the md generator </p>
</p>

### Syntax
```plsql
procedure md_example (i_input   in      number, 
                      io_inOut  in out  number,
                      o_output  out     number
                      )
```

### Parameters
Name | Description
--- | ---
`i_input` | This is the input param for the procedure
`io_inOut` | This is an in out param for the procedure
`o_output` | The return param for the procedure
 
 




### Properties
Name | Description
--- | ---
Author | M Martin
Created | 2017-Jul-06


 
