# rbe comments
Any program requires comments, 
and Rust supports a few different varieties:

## Regular Comments

These are ignored by the compiler:

    ### Line comments: 
    
    Start with // and continue to the end of the line
    
    ### Block comments: 
    
    Enclosed in /* ... */ and can span multiple lines

## Documentation Comments 
Doc Comments, which are parsed into HTML library documentation:

    /// - Generates docs for the item that follows it

    //! - Generates docs for the enclosing item 
    (typically used at the top of a file or module)
