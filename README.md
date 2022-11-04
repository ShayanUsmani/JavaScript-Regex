# Important JavaScript Regex

**For Name Only With Space:**
/^[A-Za-z ]+$/

**For Name Only Without Space:**
/^[A-Za-z]+$/

**For Numbers Only:**
/^\d+$/

**Empty and Numbers Only:**
/^(\s*|\d+)$/

**Empty and AlphaNumbers Only:**
/^(?:[a-zA-Z0-9-]+)?$/

**For EmiratesID:**
/^784-?[0-9]{4}-?[0-9]{7}-?[0-9]{1}$/

**For Phone:**
/^\+(?:[0-9]●?){6,14}[0-9]$/

**For Dubai Phone Only:**
/^\+971(?:[0-9]●?){8,8}[0-9]$/

**For Country Code:**
/^(\+?\d{1,3}|\d{1,4})$/

**For Alphanumeric Special Characters:**
/^[a-z0-9-.]+$/

**For Url:**
/^((http|https):[//]+)?(www.)?(?!.*(http|https|www.))[a-zA-Z0-9_-]+(\.[a-zA-Z]+)+(\/)?.([\w\?[a-zA-Z-_%\/@?]+)*([^\/\w\?[a-zA-Z0-9_-]+=\w+(&[a-zA-Z0-9_]+=\w+)*)?$/

**For Images Url:**
/(http(s?):)([/|.|\w|\s|-])*\.(?:jpg|jpeg|gif|png|svg|mp4)/

**For Youtube Url:**
/((https?):\/\/)?(www.)?[a-z0-9]+(\.[a-z]{2,}){1,3}(#?\/?[a-zA-Z0-9#]+)*\/?(\?[a-zA-Z0-9-_]+=[a-zA-Z0-9-%_]+&?)?$/

**For files Url: (pdf, doc, docx, msword)**
/(http(s?):)([/|.|\w|\s|-])*\.(?:pdf|doc|docx|msword)/

**For Lat and long:**
/^(\-)?\d+(\.\d+)*$/

**For Date Only: (YYYY-MM-DD)**
/^\d{4}-(0[1-9]|1[0-2])-(0[1-9]|[12][0-9]|3[01])$/

**For Database Timestap: (2022-01-27 00:00:00.000000 +00:00)**
/^[a-z0-9-/ -:]+$/

**For Time Only: (12:00)**
/^([01]?[0-9]|2[0-3]):[0-5][0-9]$/

**For Date and Time: (01-12-2022 12:00)**
/\d\d-\d\d-\d\d\d\d \d\d:\d\d/

**For Numbers and Comma Only:**
/^[0-9,]*$/
