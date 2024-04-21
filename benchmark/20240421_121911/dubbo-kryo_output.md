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
# Warmup Iteration   1: 1.681 ops/ms
Iteration   1: 7.307 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.307 ops/ms


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
# Warmup Iteration   1: 5.639 ops/ms
Iteration   1: 11.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.913 ops/ms


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
# Warmup Iteration   1: 4.573 ops/ms
Iteration   1: 11.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.670 ops/ms


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
# Warmup Iteration   1: 3.577 ops/ms
Iteration   1: 8.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.057 ops/ms


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
# Warmup Iteration   1: 4.263 ±(99.9%) 0.086 ms/op
Iteration   1: 2.057 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.057 ms/op


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
# Warmup Iteration   1: 3.064 ±(99.9%) 0.055 ms/op
Iteration   1: 1.792 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.792 ms/op


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
# Warmup Iteration   1: 3.081 ±(99.9%) 0.054 ms/op
Iteration   1: 1.927 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.927 ms/op


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
# Warmup Iteration   1: 4.875 ±(99.9%) 0.117 ms/op
Iteration   1: 3.739 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.739 ms/op


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
# Warmup Iteration   1: 3.449 ±(99.9%) 0.087 ms/op
Iteration   1: 2.069 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.557 ms/op
                 createUser·p0.50:   1.862 ms/op
                 createUser·p0.90:   2.707 ms/op
                 createUser·p0.95:   2.941 ms/op
                 createUser·p0.99:   4.388 ms/op
                 createUser·p0.999:  24.615 ms/op
                 createUser·p0.9999: 27.197 ms/op
                 createUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15736
  mean =      2.069 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13125 
    [ 2.500,  5.000) = 2479 
    [ 5.000,  7.500) = 36 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.557 ms/op
     p(50.0000) =      1.862 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      2.941 ms/op
     p(99.0000) =      4.388 ms/op
     p(99.9000) =     24.615 ms/op
     p(99.9900) =     27.197 ms/op
     p(99.9990) =     27.197 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 3.019 ±(99.9%) 0.069 ms/op
Iteration   1: 1.676 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.581 ms/op
                 existUser·p0.50:   1.513 ms/op
                 existUser·p0.90:   2.286 ms/op
                 existUser·p0.95:   2.507 ms/op
                 existUser·p0.99:   2.990 ms/op
                 existUser·p0.999:  12.304 ms/op
                 existUser·p0.9999: 12.519 ms/op
                 existUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19215
  mean =      1.676 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1440 
    [ 1.250,  2.500) = 16772 
    [ 2.500,  3.750) = 903 
    [ 3.750,  5.000) = 3 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      1.513 ms/op
     p(90.0000) =      2.286 ms/op
     p(95.0000) =      2.507 ms/op
     p(99.0000) =      2.990 ms/op
     p(99.9000) =     12.304 ms/op
     p(99.9900) =     12.519 ms/op
     p(99.9990) =     12.534 ms/op
     p(99.9999) =     12.534 ms/op
    p(100.0000) =     12.534 ms/op


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
# Warmup Iteration   1: 3.257 ±(99.9%) 0.075 ms/op
Iteration   1: 2.105 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   0.546 ms/op
                 getUser·p0.50:   1.937 ms/op
                 getUser·p0.90:   2.540 ms/op
                 getUser·p0.95:   2.801 ms/op
                 getUser·p0.99:   5.108 ms/op
                 getUser·p0.999:  20.633 ms/op
                 getUser·p0.9999: 25.126 ms/op
                 getUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15344
  mean =      2.105 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13563 
    [ 2.500,  5.000) = 1616 
    [ 5.000,  7.500) = 69 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      1.937 ms/op
     p(90.0000) =      2.540 ms/op
     p(95.0000) =      2.801 ms/op
     p(99.0000) =      5.108 ms/op
     p(99.9000) =     20.633 ms/op
     p(99.9900) =     25.126 ms/op
     p(99.9990) =     29.295 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


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
# Warmup Iteration   1: 4.523 ±(99.9%) 0.135 ms/op
Iteration   1: 3.235 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.904 ms/op
                 listUser·p0.50:   3.142 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.468 ms/op
                 listUser·p0.999:  6.987 ms/op
                 listUser·p0.9999: 9.869 ms/op
                 listUser·p1.00:   9.880 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10046
  mean =      3.235 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 5 
    [ 1.000,  2.000) = 93 
    [ 2.000,  3.000) = 4128 
    [ 3.000,  4.000) = 4584 
    [ 4.000,  5.000) = 1046 
    [ 5.000,  6.000) = 129 
    [ 6.000,  7.000) = 52 
    [ 7.000,  8.000) = 8 
    [ 8.000,  9.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.468 ms/op
     p(99.9000) =      6.987 ms/op
     p(99.9900) =      9.869 ms/op
     p(99.9990) =      9.880 ms/op
     p(99.9999) =      9.880 ms/op
    p(100.0000) =      9.880 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.307          ops/ms
ClientSimple.existUser                       thrpt         11.913          ops/ms
ClientSimple.getUser                         thrpt         11.670          ops/ms
ClientSimple.listUser                        thrpt          8.057          ops/ms
ClientSimple.createUser                       avgt          2.057           ms/op
ClientSimple.existUser                        avgt          1.792           ms/op
ClientSimple.getUser                          avgt          1.927           ms/op
ClientSimple.listUser                         avgt          3.739           ms/op
ClientSimple.createUser                     sample  15736   2.069 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.557           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.862           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.707           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.941           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.388           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.615           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.197           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.197           ms/op
ClientSimple.existUser                      sample  19215   1.676 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.581           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.513           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.286           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.507           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.990           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.304           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.519           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.534           ms/op
ClientSimple.getUser                        sample  15344   2.105 ± 0.034   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.546           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.937           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.540           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.801           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.108           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.633           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.126           ms/op
ClientSimple.getUser:getUser·p1.00          sample         29.295           ms/op
ClientSimple.listUser                       sample  10046   3.235 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.904           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.142           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.088           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.468           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.987           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.869           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.880           ms/op

Benchmark result is saved to 1713701676923.json
