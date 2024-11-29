
Amaç: .NET Core kullanarak etkinlikleri yönetmeye yönelik bir uygulamayı geliştirmektir. Detay : .NET Core MVC, .NET Core Identity kütüphanesi, in memory cache, Bootstrap, MySQL

Kütüphane Versiyon: 7.0

*** App setting dosyasında connection string' de yer alan uid ve pwd alanlarını kendi bilgisayarınızda veya sunucunuzda mevcut olan MySQL DB' nin userid ve password' ü bu alana ekledikten sonra projeyi build ve run yapmanız yeterli olacaktır. 

"server=localhost;port=3306;database=myprojectdb;uid=maviucakuser;pwd=Ay*24*Seh;"

Kullanıcı oluşturma, kimlik kontrolü, kullanıcı rol işemleri için Microsoft.AspNetCore.Identity.EntityFrameworkCore kütüphanesi kullanıldı.

ORM aracı olarak .Net Entity Framework Core kullanıldı.

Proje VS Code ile geliştirildiği için arayüzde View' leri oluşturmak için Microsoft.VisualStudio.Web.CodeGeneration.Design kütüphanesi kullanıldı.

MySQL DB kullanıldığından Pomelo.EntityFrameworkCore.MySql kütüphanesi kullanılmıştır.
