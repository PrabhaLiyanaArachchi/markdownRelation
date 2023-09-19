# markdownRelation
Sep 18,2023
---
##Relation 1
|**Bookid**   |**BookName**     |**Authorid**|
|---          |---              |----        |
|01           |odyssey          |101         |
|02           |illiad           |101         |
|03           |politics         |102         |
|04           |Republic         |103         |
|05           |Voltaire         |104         |

##Relation 2
|**Authorid** |**AuthorName**   |**Bookid**  |
|---          |---              |---         |
|101          |  homer          |01          |
|101          |  homer          |02          |
|102          |  Aristotle      |03          |
|103          | plato           |04          |
|104          | candide         |05          |

##Cross Product

##Relation 1 X Relation 2

|**Bookid**   |**BookName**     |**Authorid**|**Authorid** |**AuthorName**   |**Bookid**  |
|---          |---              |---         |---          |---              |---         |
|01           |odyssey          |101         |101          |  homer          |01          |
|01           |odyssey          |101         |101          |  homer          |02          |
|01           |odyssey          |101         |102          |  Aristotle      |03          |
|01           |odyssey          |101         |103          | plato           |04          |
|01           |odyssey          |101         |104          | candide         |05          |
|02           |illiad           |101         |101          |  homer          |01          |
|02           |illiad           |101         |101          |  homer          |02          |
|02           |illiad           |101         |102          |  Aristotle      |03          |
|02           |illiad           |101         |103          | plato           |04          |
|02           |illiad           |101         |104          | candide         |05          |
|03           |politics         |102         |101          |  homer          |01          |
|03           |politics         |102         |101          |  homer          |02          |
|03           |politics         |102         |102          |  Aristotle      |03          |
|03           |politics         |102         |103          | plato           |04          |
|03           |politics         |102         |104          | candide         |05          |
|04           |Republic         |103         |101          |  homer          |01          |
|04           |Republic         |103         |101          |  homer          |02          |
|04           |Republic         |103         |102          |  Aristotle      |03          |
|04           |Republic         |103         |103          | plato           |04          |
|04           |Republic         |103         |104          | candide         |05          |
|05           |Voltaire         |104         |101          |  homer          |01          |
|05           |Voltaire         |104         |101          |  homer          |02          |
|05           |Voltaire         |104         |102          |  Aristotle      |03          |
|05           |Voltaire         |104         |103          | plato           |04          |
|05           |Voltaire         |104         |104          | candide         |05          |

##The writers who has written more than one book

##Filtering

##Relation1.Authorid=Relation2.Authorid && Relation1.bookid=Relation2.bookid

|**Bookid**   |**BookName**     |**Authorid**|**Authorid** |**AuthorName**   |**Bookid**  |
|---          |---              |---         |---          |---              |---         |
|01           |odyssey          |101         |101          |  homer          |01          |
|02           |illiad           |101         |101          |  homer          |02          |

## Relation1.Bookname,Relation2.AuthorName
|**BookName**     |**AuthorName**   |
|---              |---              |
|odyssey          |homer            |
|illiad           |homer            |

