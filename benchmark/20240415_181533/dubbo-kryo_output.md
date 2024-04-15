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
# Warmup Iteration   1: 1.933 ops/ms
Iteration   1: 7.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.098 ops/ms


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
# Warmup Iteration   1: 6.516 ops/ms
Iteration   1: 11.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.582 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.519 ops/ms
Iteration   1: 12.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.616 ops/ms


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
# Warmup Iteration   1: 5.117 ops/ms
Iteration   1: 8.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.772 ops/ms


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
# Warmup Iteration   1: 3.913 ±(99.9%) 0.078 ms/op
Iteration   1: 2.176 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.176 ms/op


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
# Warmup Iteration   1: 2.989 ±(99.9%) 0.066 ms/op
Iteration   1: 1.746 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.746 ms/op


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
# Warmup Iteration   1: 3.343 ±(99.9%) 0.061 ms/op
Iteration   1: 2.210 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.210 ms/op


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
# Warmup Iteration   1: 4.951 ±(99.9%) 0.141 ms/op
Iteration   1: 3.412 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.412 ms/op


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
# Warmup Iteration   1: 3.476 ±(99.9%) 0.078 ms/op
Iteration   1: 2.202 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.562 ms/op
                 createUser·p0.50:   2.179 ms/op
                 createUser·p0.90:   2.658 ms/op
                 createUser·p0.95:   2.875 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  21.266 ms/op
                 createUser·p0.9999: 23.266 ms/op
                 createUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14505
  mean =      2.202 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11959 
    [ 2.500,  5.000) = 2356 
    [ 5.000,  7.500) = 125 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      2.179 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      2.875 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     21.266 ms/op
     p(99.9900) =     23.266 ms/op
     p(99.9990) =     23.724 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 3.056 ±(99.9%) 0.070 ms/op
Iteration   1: 1.872 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.530 ms/op
                 existUser·p0.50:   1.716 ms/op
                 existUser·p0.90:   2.388 ms/op
                 existUser·p0.95:   2.699 ms/op
                 existUser·p0.99:   3.325 ms/op
                 existUser·p0.999:  13.677 ms/op
                 existUser·p0.9999: 14.215 ms/op
                 existUser·p1.00:   14.238 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17071
  mean =      1.872 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 156 
    [ 1.250,  2.500) = 15517 
    [ 2.500,  3.750) = 1291 
    [ 3.750,  5.000) = 38 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      1.716 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.699 ms/op
     p(99.0000) =      3.325 ms/op
     p(99.9000) =     13.677 ms/op
     p(99.9900) =     14.215 ms/op
     p(99.9990) =     14.238 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 3.455 ±(99.9%) 0.090 ms/op
Iteration   1: 1.946 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.645 ms/op
                 getUser·p0.50:   1.821 ms/op
                 getUser·p0.90:   2.322 ms/op
                 getUser·p0.95:   2.527 ms/op
                 getUser·p0.99:   3.420 ms/op
                 getUser·p0.999:  18.860 ms/op
                 getUser·p0.9999: 19.148 ms/op
                 getUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16431
  mean =      1.946 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 15459 
    [ 2.500,  3.750) = 794 
    [ 3.750,  5.000) = 19 
    [ 5.000,  6.250) = 22 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.322 ms/op
     p(95.0000) =      2.527 ms/op
     p(99.0000) =      3.420 ms/op
     p(99.9000) =     18.860 ms/op
     p(99.9900) =     19.148 ms/op
     p(99.9990) =     19.169 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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
# Warmup Iteration   1: 4.617 ±(99.9%) 0.140 ms/op
Iteration   1: 3.499 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   0.702 ms/op
                 listUser·p0.50:   3.318 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  17.793 ms/op
                 listUser·p0.9999: 19.857 ms/op
                 listUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9150
  mean =      3.499 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 18 
    [ 1.250,  2.500) = 554 
    [ 2.500,  3.750) = 5756 
    [ 3.750,  5.000) = 2425 
    [ 5.000,  6.250) = 248 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     17.793 ms/op
     p(99.9900) =     19.857 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.098          ops/ms
ClientSimple.existUser                       thrpt         11.582          ops/ms
ClientSimple.getUser                         thrpt         12.616          ops/ms
ClientSimple.listUser                        thrpt          8.772          ops/ms
ClientSimple.createUser                       avgt          2.176           ms/op
ClientSimple.existUser                        avgt          1.746           ms/op
ClientSimple.getUser                          avgt          2.210           ms/op
ClientSimple.listUser                         avgt          3.412           ms/op
ClientSimple.createUser                     sample  14505   2.202 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.562           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.179           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.658           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.875           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.415           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.266           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.266           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.724           ms/op
ClientSimple.existUser                      sample  17071   1.872 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.530           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.716           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.388           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.699           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.325           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.677           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.215           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.238           ms/op
ClientSimple.getUser                        sample  16431   1.946 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.645           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.821           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.322           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.527           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.420           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.860           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.148           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.169           ms/op
ClientSimple.listUser                       sample   9150   3.499 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.702           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.318           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.825           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.184           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.793           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.857           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.857           ms/op

Benchmark result is saved to 1713204658596.json
