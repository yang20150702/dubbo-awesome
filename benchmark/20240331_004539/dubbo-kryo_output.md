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
# Warmup Iteration   1: 1.797 ops/ms
Iteration   1: 8.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.103 ops/ms


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
# Warmup Iteration   1: 6.306 ops/ms
Iteration   1: 13.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.077 ops/ms


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
# Warmup Iteration   1: 6.807 ops/ms
Iteration   1: 14.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.035 ops/ms


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
# Warmup Iteration   1: 5.418 ops/ms
Iteration   1: 8.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.377 ops/ms


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
# Warmup Iteration   1: 3.785 ±(99.9%) 0.061 ms/op
Iteration   1: 2.141 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.141 ms/op


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
# Warmup Iteration   1: 3.381 ±(99.9%) 0.058 ms/op
Iteration   1: 2.076 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.076 ms/op


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
# Warmup Iteration   1: 3.147 ±(99.9%) 0.050 ms/op
Iteration   1: 2.076 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.076 ms/op


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
# Warmup Iteration   1: 4.472 ±(99.9%) 0.077 ms/op
Iteration   1: 3.212 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.212 ms/op


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
# Warmup Iteration   1: 4.179 ±(99.9%) 0.130 ms/op
Iteration   1: 2.207 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   1.966 ms/op
                 createUser·p0.90:   2.527 ms/op
                 createUser·p0.95:   2.802 ms/op
                 createUser·p0.99:   8.684 ms/op
                 createUser·p0.999:  18.678 ms/op
                 createUser·p0.9999: 20.709 ms/op
                 createUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14719
  mean =      2.207 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13120 
    [ 2.500,  5.000) = 1367 
    [ 5.000,  7.500) = 39 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      1.966 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      8.684 ms/op
     p(99.9000) =     18.678 ms/op
     p(99.9900) =     20.709 ms/op
     p(99.9990) =     20.709 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 2.899 ±(99.9%) 0.071 ms/op
Iteration   1: 1.813 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.488 ms/op
                 existUser·p0.50:   1.739 ms/op
                 existUser·p0.90:   2.183 ms/op
                 existUser·p0.95:   2.376 ms/op
                 existUser·p0.99:   3.207 ms/op
                 existUser·p0.999:  15.868 ms/op
                 existUser·p0.9999: 17.438 ms/op
                 existUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17623
  mean =      1.813 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 630 
    [ 1.250,  2.500) = 16350 
    [ 2.500,  3.750) = 569 
    [ 3.750,  5.000) = 26 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.488 ms/op
     p(50.0000) =      1.739 ms/op
     p(90.0000) =      2.183 ms/op
     p(95.0000) =      2.376 ms/op
     p(99.0000) =      3.207 ms/op
     p(99.9000) =     15.868 ms/op
     p(99.9900) =     17.438 ms/op
     p(99.9990) =     18.612 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


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
# Warmup Iteration   1: 3.270 ±(99.9%) 0.088 ms/op
Iteration   1: 2.236 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.544 ms/op
                 getUser·p0.50:   2.249 ms/op
                 getUser·p0.90:   2.802 ms/op
                 getUser·p0.95:   2.929 ms/op
                 getUser·p0.99:   3.326 ms/op
                 getUser·p0.999:  11.627 ms/op
                 getUser·p0.9999: 12.124 ms/op
                 getUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14339
  mean =      2.236 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 170 
    [ 1.250,  2.500) = 9714 
    [ 2.500,  3.750) = 4345 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      2.249 ms/op
     p(90.0000) =      2.802 ms/op
     p(95.0000) =      2.929 ms/op
     p(99.0000) =      3.326 ms/op
     p(99.9000) =     11.627 ms/op
     p(99.9900) =     12.124 ms/op
     p(99.9990) =     12.124 ms/op
     p(99.9999) =     12.124 ms/op
    p(100.0000) =     12.124 ms/op


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
# Warmup Iteration   1: 4.485 ±(99.9%) 0.152 ms/op
Iteration   1: 3.096 ±(99.9%) 0.051 ms/op
                 listUser·p0.00:   1.037 ms/op
                 listUser·p0.50:   2.822 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  29.327 ms/op
                 listUser·p0.9999: 30.108 ms/op
                 listUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10328
  mean =      3.096 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1032 
    [ 2.500,  5.000) = 9158 
    [ 5.000,  7.500) = 106 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.037 ms/op
     p(50.0000) =      2.822 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     29.327 ms/op
     p(99.9900) =     30.108 ms/op
     p(99.9990) =     30.114 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.103          ops/ms
ClientSimple.existUser                       thrpt         13.077          ops/ms
ClientSimple.getUser                         thrpt         14.035          ops/ms
ClientSimple.listUser                        thrpt          8.377          ops/ms
ClientSimple.createUser                       avgt          2.141           ms/op
ClientSimple.existUser                        avgt          2.076           ms/op
ClientSimple.getUser                          avgt          2.076           ms/op
ClientSimple.listUser                         avgt          3.212           ms/op
ClientSimple.createUser                     sample  14719   2.207 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.754           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.966           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.527           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.802           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.684           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.678           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.709           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.709           ms/op
ClientSimple.existUser                      sample  17623   1.813 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.488           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.739           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.183           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.376           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.207           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.868           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.438           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.612           ms/op
ClientSimple.getUser                        sample  14339   2.236 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.544           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.249           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.802           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.929           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.326           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.627           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.124           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.124           ms/op
ClientSimple.listUser                       sample  10328   3.096 ± 0.051   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.037           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.822           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.953           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.439           ms/op
ClientSimple.listUser:listUser·p0.999       sample         29.327           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         30.108           ms/op
ClientSimple.listUser:listUser·p1.00        sample         30.114           ms/op

Benchmark result is saved to 1711845669399.json
