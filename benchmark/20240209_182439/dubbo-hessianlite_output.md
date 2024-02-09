# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.335 ops/ms
Iteration   1: 6.128 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.128 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.715 ops/ms
Iteration   1: 12.948 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.948 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.820 ops/ms
Iteration   1: 9.559 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.559 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.452 ops/ms
Iteration   1: 3.884 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.884 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.689 ±(99.9%) 0.096 ms/op
Iteration   1: 3.248 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.248 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.047 ±(99.9%) 0.033 ms/op
Iteration   1: 1.721 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.721 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.331 ±(99.9%) 0.078 ms/op
Iteration   1: 3.013 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.013 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.246 ±(99.9%) 0.231 ms/op
Iteration   1: 8.305 ±(99.9%) 0.093 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.305 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.798 ±(99.9%) 0.106 ms/op
Iteration   1: 2.952 ±(99.9%) 0.054 ms/op
                 createUser·p0.00:   0.522 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   11.509 ms/op
                 createUser·p0.999:  27.329 ms/op
                 createUser·p0.9999: 27.522 ms/op
                 createUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10952
  mean =      2.952 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4275 
    [ 2.500,  5.000) = 6283 
    [ 5.000,  7.500) = 222 
    [ 7.500, 10.000) = 22 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =     11.509 ms/op
     p(99.9000) =     27.329 ms/op
     p(99.9900) =     27.522 ms/op
     p(99.9990) =     27.525 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.388 ±(99.9%) 0.088 ms/op
Iteration   1: 1.844 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.294 ms/op
                 existUser·p0.50:   1.798 ms/op
                 existUser·p0.90:   2.286 ms/op
                 existUser·p0.95:   2.486 ms/op
                 existUser·p0.99:   3.248 ms/op
                 existUser·p0.999:  6.029 ms/op
                 existUser·p0.9999: 6.164 ms/op
                 existUser·p1.00:   6.177 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17643
  mean =      1.844 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 29 
    [0.500, 1.000) = 204 
    [1.000, 1.500) = 2454 
    [1.500, 2.000) = 9912 
    [2.000, 2.500) = 4204 
    [2.500, 3.000) = 619 
    [3.000, 3.500) = 105 
    [3.500, 4.000) = 21 
    [4.000, 4.500) = 25 
    [4.500, 5.000) = 5 
    [5.000, 5.500) = 20 
    [5.500, 6.000) = 21 
    [6.000, 6.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.294 ms/op
     p(50.0000) =      1.798 ms/op
     p(90.0000) =      2.286 ms/op
     p(95.0000) =      2.486 ms/op
     p(99.0000) =      3.248 ms/op
     p(99.9000) =      6.029 ms/op
     p(99.9900) =      6.164 ms/op
     p(99.9990) =      6.177 ms/op
     p(99.9999) =      6.177 ms/op
    p(100.0000) =      6.177 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.425 ±(99.9%) 0.107 ms/op
Iteration   1: 2.737 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.462 ms/op
                 getUser·p0.50:   2.609 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.882 ms/op
                 getUser·p0.999:  8.591 ms/op
                 getUser·p0.9999: 10.393 ms/op
                 getUser·p1.00:   10.437 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11789
  mean =      2.737 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 5 
    [ 1.000,  2.000) = 473 
    [ 2.000,  3.000) = 8253 
    [ 3.000,  4.000) = 2626 
    [ 4.000,  5.000) = 338 
    [ 5.000,  6.000) = 66 
    [ 6.000,  7.000) = 5 
    [ 7.000,  8.000) = 4 
    [ 8.000,  9.000) = 8 
    [ 9.000, 10.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.882 ms/op
     p(99.9000) =      8.591 ms/op
     p(99.9900) =     10.393 ms/op
     p(99.9990) =     10.437 ms/op
     p(99.9999) =     10.437 ms/op
    p(100.0000) =     10.437 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.598 ±(99.9%) 0.535 ms/op
Iteration   1: 8.804 ±(99.9%) 0.113 ms/op
                 listUser·p0.00:   3.203 ms/op
                 listUser·p0.50:   8.585 ms/op
                 listUser·p0.90:   11.485 ms/op
                 listUser·p0.95:   12.372 ms/op
                 listUser·p0.99:   14.920 ms/op
                 listUser·p0.999:  19.226 ms/op
                 listUser·p0.9999: 21.234 ms/op
                 listUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3636
  mean =      8.804 ±(99.9%) 0.113 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 70 
    [ 5.000,  7.500) = 850 
    [ 7.500, 10.000) = 1909 
    [10.000, 12.500) = 645 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.203 ms/op
     p(50.0000) =      8.585 ms/op
     p(90.0000) =     11.485 ms/op
     p(95.0000) =     12.372 ms/op
     p(99.0000) =     14.920 ms/op
     p(99.9000) =     19.226 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     21.234 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.128          ops/ms
Client.existUser                       thrpt         12.948          ops/ms
Client.getUser                         thrpt          9.559          ops/ms
Client.listUser                        thrpt          3.884          ops/ms
Client.createUser                       avgt          3.248           ms/op
Client.existUser                        avgt          1.721           ms/op
Client.getUser                          avgt          3.013           ms/op
Client.listUser                         avgt          8.305           ms/op
Client.createUser                     sample  10952   2.952 ± 0.054   ms/op
Client.createUser:createUser·p0.00    sample          0.522           ms/op
Client.createUser:createUser·p0.50    sample          2.609           ms/op
Client.createUser:createUser·p0.90    sample          3.772           ms/op
Client.createUser:createUser·p0.95    sample          4.260           ms/op
Client.createUser:createUser·p0.99    sample         11.509           ms/op
Client.createUser:createUser·p0.999   sample         27.329           ms/op
Client.createUser:createUser·p0.9999  sample         27.522           ms/op
Client.createUser:createUser·p1.00    sample         27.525           ms/op
Client.existUser                      sample  17643   1.844 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.294           ms/op
Client.existUser:existUser·p0.50      sample          1.798           ms/op
Client.existUser:existUser·p0.90      sample          2.286           ms/op
Client.existUser:existUser·p0.95      sample          2.486           ms/op
Client.existUser:existUser·p0.99      sample          3.248           ms/op
Client.existUser:existUser·p0.999     sample          6.029           ms/op
Client.existUser:existUser·p0.9999    sample          6.164           ms/op
Client.existUser:existUser·p1.00      sample          6.177           ms/op
Client.getUser                        sample  11789   2.737 ± 0.019   ms/op
Client.getUser:getUser·p0.00          sample          0.462           ms/op
Client.getUser:getUser·p0.50          sample          2.609           ms/op
Client.getUser:getUser·p0.90          sample          3.391           ms/op
Client.getUser:getUser·p0.95          sample          3.760           ms/op
Client.getUser:getUser·p0.99          sample          4.882           ms/op
Client.getUser:getUser·p0.999         sample          8.591           ms/op
Client.getUser:getUser·p0.9999        sample         10.393           ms/op
Client.getUser:getUser·p1.00          sample         10.437           ms/op
Client.listUser                       sample   3636   8.804 ± 0.113   ms/op
Client.listUser:listUser·p0.00        sample          3.203           ms/op
Client.listUser:listUser·p0.50        sample          8.585           ms/op
Client.listUser:listUser·p0.90        sample         11.485           ms/op
Client.listUser:listUser·p0.95        sample         12.372           ms/op
Client.listUser:listUser·p0.99        sample         14.920           ms/op
Client.listUser:listUser·p0.999       sample         19.226           ms/op
Client.listUser:listUser·p0.9999      sample         21.234           ms/op
Client.listUser:listUser·p1.00        sample         21.234           ms/op
