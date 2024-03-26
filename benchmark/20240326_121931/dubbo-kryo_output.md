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
# Warmup Iteration   1: 1.805 ops/ms
Iteration   1: 7.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.561 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.276 ops/ms
Iteration   1: 11.495 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.495 ops/ms


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
# Warmup Iteration   1: 5.894 ops/ms
Iteration   1: 13.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.475 ops/ms


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
# Warmup Iteration   1: 4.804 ops/ms
Iteration   1: 8.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.006 ops/ms


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
# Warmup Iteration   1: 4.614 ±(99.9%) 0.116 ms/op
Iteration   1: 2.030 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.030 ms/op


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
# Warmup Iteration   1: 3.511 ±(99.9%) 0.061 ms/op
Iteration   1: 1.861 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.861 ms/op


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
# Warmup Iteration   1: 3.402 ±(99.9%) 0.062 ms/op
Iteration   1: 1.923 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.923 ms/op


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
# Warmup Iteration   1: 4.323 ±(99.9%) 0.096 ms/op
Iteration   1: 3.153 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.153 ms/op


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
# Warmup Iteration   1: 3.722 ±(99.9%) 0.089 ms/op
Iteration   1: 2.129 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.564 ms/op
                 createUser·p0.50:   1.948 ms/op
                 createUser·p0.90:   2.830 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  15.466 ms/op
                 createUser·p0.9999: 15.581 ms/op
                 createUser·p1.00:   15.614 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15007
  mean =      2.129 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 12057 
    [ 2.500,  3.750) = 2495 
    [ 3.750,  5.000) = 185 
    [ 5.000,  6.250) = 140 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      1.948 ms/op
     p(90.0000) =      2.830 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     15.466 ms/op
     p(99.9900) =     15.581 ms/op
     p(99.9990) =     15.614 ms/op
     p(99.9999) =     15.614 ms/op
    p(100.0000) =     15.614 ms/op


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
# Warmup Iteration   1: 3.464 ±(99.9%) 0.184 ms/op
Iteration   1: 2.262 ±(99.9%) 0.142 ms/op
                 existUser·p0.00:   0.293 ms/op
                 existUser·p0.50:   1.870 ms/op
                 existUser·p0.90:   2.503 ms/op
                 existUser·p0.95:   2.777 ms/op
                 existUser·p0.99:   7.283 ms/op
                 existUser·p0.999:  105.279 ms/op
                 existUser·p0.9999: 125.381 ms/op
                 existUser·p1.00:   125.436 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14196
  mean =      2.262 ±(99.9%) 0.142 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 14109 
    [ 12.500,  25.000) = 11 
    [ 25.000,  37.500) = 37 
    [ 37.500,  50.000) = 1 
    [ 50.000,  62.500) = 9 
    [ 62.500,  75.000) = 3 
    [ 75.000,  87.500) = 1 
    [ 87.500, 100.000) = 5 
    [100.000, 112.500) = 11 
    [112.500, 125.000) = 7 
    [125.000, 137.500) = 2 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.293 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =    105.279 ms/op
     p(99.9900) =    125.381 ms/op
     p(99.9990) =    125.436 ms/op
     p(99.9999) =    125.436 ms/op
    p(100.0000) =    125.436 ms/op


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.256 ms/op
Iteration   1: 2.155 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.490 ms/op
                 getUser·p0.50:   2.079 ms/op
                 getUser·p0.90:   2.773 ms/op
                 getUser·p0.95:   2.925 ms/op
                 getUser·p0.99:   4.020 ms/op
                 getUser·p0.999:  10.282 ms/op
                 getUser·p0.9999: 11.100 ms/op
                 getUser·p1.00:   11.108 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14840
  mean =      2.155 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 219 
    [ 1.250,  2.500) = 11338 
    [ 2.500,  3.750) = 3093 
    [ 3.750,  5.000) = 91 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      2.079 ms/op
     p(90.0000) =      2.773 ms/op
     p(95.0000) =      2.925 ms/op
     p(99.0000) =      4.020 ms/op
     p(99.9000) =     10.282 ms/op
     p(99.9900) =     11.100 ms/op
     p(99.9990) =     11.108 ms/op
     p(99.9999) =     11.108 ms/op
    p(100.0000) =     11.108 ms/op


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
# Warmup Iteration   1: 4.039 ±(99.9%) 0.110 ms/op
Iteration   1: 3.411 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   0.657 ms/op
                 listUser·p0.50:   3.441 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.252 ms/op
                 listUser·p0.999:  22.270 ms/op
                 listUser·p0.9999: 24.019 ms/op
                 listUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9381
  mean =      3.411 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1565 
    [ 2.500,  5.000) = 7625 
    [ 5.000,  7.500) = 130 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.252 ms/op
     p(99.9000) =     22.270 ms/op
     p(99.9900) =     24.019 ms/op
     p(99.9990) =     24.019 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           7.561          ops/ms
ClientSimple.existUser                       thrpt          11.495          ops/ms
ClientSimple.getUser                         thrpt          13.475          ops/ms
ClientSimple.listUser                        thrpt           8.006          ops/ms
ClientSimple.createUser                       avgt           2.030           ms/op
ClientSimple.existUser                        avgt           1.861           ms/op
ClientSimple.getUser                          avgt           1.923           ms/op
ClientSimple.listUser                         avgt           3.153           ms/op
ClientSimple.createUser                     sample  15007    2.129 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.564           ms/op
ClientSimple.createUser:createUser·p0.50    sample           1.948           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.830           ms/op
ClientSimple.createUser:createUser·p0.95    sample           3.117           ms/op
ClientSimple.createUser:createUser·p0.99    sample           5.530           ms/op
ClientSimple.createUser:createUser·p0.999   sample          15.466           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          15.581           ms/op
ClientSimple.createUser:createUser·p1.00    sample          15.614           ms/op
ClientSimple.existUser                      sample  14196    2.262 ± 0.142   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.293           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.870           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.503           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.777           ms/op
ClientSimple.existUser:existUser·p0.99      sample           7.283           ms/op
ClientSimple.existUser:existUser·p0.999     sample         105.279           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         125.381           ms/op
ClientSimple.existUser:existUser·p1.00      sample         125.436           ms/op
ClientSimple.getUser                        sample  14840    2.155 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.490           ms/op
ClientSimple.getUser:getUser·p0.50          sample           2.079           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.773           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.925           ms/op
ClientSimple.getUser:getUser·p0.99          sample           4.020           ms/op
ClientSimple.getUser:getUser·p0.999         sample          10.282           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          11.100           ms/op
ClientSimple.getUser:getUser·p1.00          sample          11.108           ms/op
ClientSimple.listUser                       sample   9381    3.411 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample           0.657           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.441           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.489           ms/op
ClientSimple.listUser:listUser·p0.99        sample           6.252           ms/op
ClientSimple.listUser:listUser·p0.999       sample          22.270           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          24.019           ms/op
ClientSimple.listUser:listUser·p1.00        sample          24.019           ms/op

Benchmark result is saved to 1711455323150.json
