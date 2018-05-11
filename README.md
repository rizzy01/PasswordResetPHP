# PasswordResetPHP
PHP MySQL FileMaker User Registration System with Secure Password Reset and Multiple File Upload

User registration and secure password reset code.
With registration, login, and password reset pages.

Also includes code for uploading files to your web server and to a <a href="https://cloudinary.com/">Cloudinary</a> account.

Built using PHP, MySQL, FileMaker API for PHP, FileMaker, jQuery and Bootstrap 4.
You can use either MySQL or FileMaker as your database. Sample MySQL and FileMaker databases included.

The FileMaker database includes scripts to dynamically create FileMaker accounts and put uploaded files into a container field.


<h2>NOTE:</h2>
<strong>The FileMaker username is Admin, password is admin.</strong>

 
<h2>NOTE:</h2> 
This code stores passwords in the database in plain text. <strong>Never store passwords in plain text!</strong> It is only done here for demonstration purposes. If you use this code in a real site remove all references to the <strong>password_plaintext</strong> field from <strong>register.php</strong> and <strong>reset_password.php</strong> and remove the <strong>password_plaintext</strong> field from the <strong>user</strong> table.


<h2>Inspiration</h2>
<ul>
<li><a href="https://www.troyhunt.com/everything-you-ever-wanted-to-know/" target="_blank">Everything you ever wanted to know about building a secure password reset feature</a></li>

<li><a href="https://gist.github.com/N-Porsh/7766039" target="_blank">PHP: simple multiple file upload</a></li>

<li><a href="https://cloudinary.com/blog/file_upload_with_php#handling_file_upload_with_cloudinary
" target="_blank">Handling File Upload With Cloudinary</a></li>
</ul>

![registration form](https://github.com/asktami/PasswordResetPHP/blob/master/img/Screenshots/1_registration_form.png)
