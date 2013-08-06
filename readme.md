# CodeIgniter Helper: Read file into string (alternative method)

**ci-file_get_contents-alt**

## About this helper

This CodeIgniter's Helper replaces the [file_get_contents()](http://php.net/manual/en/function.file-get-contents.php) method in systems where it's not supported or disabled.  
Its usage is recommended for CodeIgniter 2 or greater.  
  
This helper is based on Pear's [PHP_Compat](http://pear.php.net/package/PHP_Compat/download/) package.

## Usage

```php
$this->load->helper("file_get_contents_alt"); // load helper
$url = "http://graph.facebook.com/facebook"; // replace this URL with the preferred one
$result = file_get_contents_alt($url); // get string result
echo $result;
```

![Ale Mohamad](http://codeigniter.alemohamad.com/images/logo2012am.png)
