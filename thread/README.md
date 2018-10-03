This is about thread and concurrency in java which contains following parts:
# Thread and Runnable
Thread类为底层操作系统的线程体系框架提供一套统一接口。单个的操作系统线程和一个Thread对象关联。

Runnable接口为关联Thread对象的线程提供执行代码。这些代码放在Runnable的void run()方法中，这个方法虽然不接受任何参数并且没有返回值，但是有可能抛出异常。


