# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.787 ops/ms
Iteration   1: 7.345 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.345 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.866 ops/ms
Iteration   1: 12.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.300 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.321 ops/ms
Iteration   1: 12.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.655 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.698 ops/ms
Iteration   1: 8.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.560 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.968 ±(99.9%) 0.071 ms/op
Iteration   1: 2.129 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.129 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.248 ±(99.9%) 0.051 ms/op
Iteration   1: 1.978 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.978 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.575 ±(99.9%) 0.084 ms/op
Iteration   1: 1.814 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.814 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.405 ±(99.9%) 0.105 ms/op
Iteration   1: 3.344 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.344 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.378 ±(99.9%) 0.076 ms/op
Iteration   1: 2.191 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.462 ms/op
                 createUser·p0.50:   2.079 ms/op
                 createUser·p0.90:   2.666 ms/op
                 createUser·p0.95:   2.855 ms/op
                 createUser·p0.99:   5.572 ms/op
                 createUser·p0.999:  22.708 ms/op
                 createUser·p0.9999: 23.767 ms/op
                 createUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14585
  mean =      2.191 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12181 
    [ 2.500,  5.000) = 2238 
    [ 5.000,  7.500) = 85 
    [ 7.500, 10.000) = 22 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      2.079 ms/op
     p(90.0000) =      2.666 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      5.572 ms/op
     p(99.9000) =     22.708 ms/op
     p(99.9900) =     23.767 ms/op
     p(99.9990) =     24.248 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.997 ±(99.9%) 0.063 ms/op
Iteration   1: 2.046 ±(99.9%) 0.086 ms/op
                 existUser·p0.00:   0.654 ms/op
                 existUser·p0.50:   1.804 ms/op
                 existUser·p0.90:   2.310 ms/op
                 existUser·p0.95:   2.527 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  71.303 ms/op
                 existUser·p0.9999: 72.098 ms/op
                 existUser·p1.00:   72.614 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15627
  mean =      2.046 ±(99.9%) 0.086 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15492 
    [ 5.000, 10.000) = 71 
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 29 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 15 
    [70.000, 75.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      1.804 ms/op
     p(90.0000) =      2.310 ms/op
     p(95.0000) =      2.527 ms/op
     p(99.0000) =      3.613 ms/op
     p(99.9000) =     71.303 ms/op
     p(99.9900) =     72.098 ms/op
     p(99.9990) =     72.614 ms/op
     p(99.9999) =     72.614 ms/op
    p(100.0000) =     72.614 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.256 ±(99.9%) 0.084 ms/op
Iteration   1: 2.028 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.632 ms/op
                 getUser·p0.50:   1.966 ms/op
                 getUser·p0.90:   2.507 ms/op
                 getUser·p0.95:   2.712 ms/op
                 getUser·p0.99:   4.123 ms/op
                 getUser·p0.999:  11.764 ms/op
                 getUser·p0.9999: 12.222 ms/op
                 getUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15787
  mean =      2.028 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 276 
    [ 1.250,  2.500) = 13904 
    [ 2.500,  3.750) = 1401 
    [ 3.750,  5.000) = 123 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      1.966 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.712 ms/op
     p(99.0000) =      4.123 ms/op
     p(99.9000) =     11.764 ms/op
     p(99.9900) =     12.222 ms/op
     p(99.9990) =     12.222 ms/op
     p(99.9999) =     12.222 ms/op
    p(100.0000) =     12.222 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.743 ±(99.9%) 0.146 ms/op
Iteration   1: 3.407 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.305 ms/op
                 listUser·p0.50:   3.543 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.508 ms/op
                 listUser·p0.99:   5.997 ms/op
                 listUser·p0.999:  6.903 ms/op
                 listUser·p0.9999: 8.208 ms/op
                 listUser·p1.00:   8.208 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9372
  mean =      3.407 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 13 
    [1.500, 2.000) = 368 
    [2.000, 2.500) = 1430 
    [2.500, 3.000) = 814 
    [3.000, 3.500) = 1818 
    [3.500, 4.000) = 2827 
    [4.000, 4.500) = 1618 
    [4.500, 5.000) = 260 
    [5.000, 5.500) = 101 
    [5.500, 6.000) = 31 
    [6.000, 6.500) = 71 
    [6.500, 7.000) = 12 
    [7.000, 7.500) = 3 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.543 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.508 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =      6.903 ms/op
     p(99.9900) =      8.208 ms/op
     p(99.9990) =      8.208 ms/op
     p(99.9999) =      8.208 ms/op
    p(100.0000) =      8.208 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.345          ops/ms
ClientSimple.existUser                       thrpt         12.300          ops/ms
ClientSimple.getUser                         thrpt         12.655          ops/ms
ClientSimple.listUser                        thrpt          8.560          ops/ms
ClientSimple.createUser                       avgt          2.129           ms/op
ClientSimple.existUser                        avgt          1.978           ms/op
ClientSimple.getUser                          avgt          1.814           ms/op
ClientSimple.listUser                         avgt          3.344           ms/op
ClientSimple.createUser                     sample  14585   2.191 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.462           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.079           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.666           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.855           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.572           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.708           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.767           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.248           ms/op
ClientSimple.existUser                      sample  15627   2.046 ± 0.086   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.654           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.804           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.310           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.527           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.613           ms/op
ClientSimple.existUser:existUser·p0.999     sample         71.303           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         72.098           ms/op
ClientSimple.existUser:existUser·p1.00      sample         72.614           ms/op
ClientSimple.getUser                        sample  15787   2.028 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.632           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.966           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.507           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.712           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.123           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.764           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.222           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.222           ms/op
ClientSimple.listUser                       sample   9372   3.407 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.305           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.543           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.252           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.508           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.997           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.903           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.208           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.208           ms/op

Benchmark result is saved to 1713161559093.json
