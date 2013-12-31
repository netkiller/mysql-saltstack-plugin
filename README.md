mysql-saltstack-plugin
======================

Example
-------
    select salt( '*', 'test.ping');
    
    select salt( host, 'test.ping') from mysql.user;
    
    select salt( host, 'test.ping') from mysql.user where like '192.168.%';
    
    select salt( s.host, f.fun ) from server s, function f where s.host like '192.168.%' and s.id = f.id;
    
    
