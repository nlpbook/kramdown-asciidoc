    SelectBlock        ::= SelectClause
                           ( FromClause )?
                           ( WhereClause )?

    SelectClause       ::= <SELECT> ( <ALL> | <DISTINCT> )? ( SelectRegular | SelectValue )
