# Hello, World!

This is a test. This is a test. A test is what this is. This is a test.

## CredentialSubjectClass
| Class                   | Mixins                  |  Class URI            | Slots                 |
| ----------------------- | ----------------------- |  -------------------- | --------------------- |
| PersonClass             | PersonIdentityClass     |  schema:Person        | address<br>passport<br>drivingPermit<br>residencePermit 
| PersonIdentityClass     |                         |  name<br>birthDate   |
| BirthDateClass          | ValidityClass           |                       | value (range: date)   |
| AddressClass            |                         |  address             |



To change the title of the page or include additional files you'll need to edit `source/index.html.md.erb`.

If you want slightly more control, you can always use <strong>HTML</strong>.

For more detail and troubleshooting, take a look at the `README.md` file in the root of this project.
