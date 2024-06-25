# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.758 ops/ms
Iteration   1: 6.944 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.944 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.602 ops/ms
Iteration   1: 12.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.216 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.072 ops/ms
Iteration   1: 13.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.363 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.481 ops/ms
Iteration   1: 8.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.400 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.474 ±(99.9%) 0.075 ms/op
Iteration   1: 2.263 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.263 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.405 ±(99.9%) 0.057 ms/op
Iteration   1: 1.951 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.951 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.120 ±(99.9%) 0.059 ms/op
Iteration   1: 2.027 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.027 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.487 ±(99.9%) 0.088 ms/op
Iteration   1: 3.108 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.108 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.625 ±(99.9%) 0.093 ms/op
Iteration   1: 2.172 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   1.993 ms/op
                 createUser·p0.90:   2.576 ms/op
                 createUser·p0.95:   2.900 ms/op
                 createUser·p0.99:   7.689 ms/op
                 createUser·p0.999:  18.973 ms/op
                 createUser·p0.9999: 20.018 ms/op
                 createUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14722
  mean =      2.172 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12960 
    [ 2.500,  5.000) = 1454 
    [ 5.000,  7.500) = 150 
    [ 7.500, 10.000) = 61 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      1.993 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.900 ms/op
     p(99.0000) =      7.689 ms/op
     p(99.9000) =     18.973 ms/op
     p(99.9900) =     20.018 ms/op
     p(99.9990) =     20.251 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.787 ±(99.9%) 0.070 ms/op
Iteration   1: 1.889 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.578 ms/op
                 existUser·p0.50:   1.720 ms/op
                 existUser·p0.90:   2.417 ms/op
                 existUser·p0.95:   2.662 ms/op
                 existUser·p0.99:   3.810 ms/op
                 existUser·p0.999:  16.665 ms/op
                 existUser·p0.9999: 17.241 ms/op
                 existUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16924
  mean =      1.889 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 99 
    [ 1.250,  2.500) = 15515 
    [ 2.500,  3.750) = 1133 
    [ 3.750,  5.000) = 64 
    [ 5.000,  6.250) = 70 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      1.720 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =      3.810 ms/op
     p(99.9000) =     16.665 ms/op
     p(99.9900) =     17.241 ms/op
     p(99.9990) =     17.990 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.254 ±(99.9%) 0.088 ms/op
Iteration   1: 2.119 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   2.023 ms/op
                 getUser·p0.90:   2.568 ms/op
                 getUser·p0.95:   2.826 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  12.009 ms/op
                 getUser·p0.9999: 12.238 ms/op
                 getUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15077
  mean =      2.119 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 13199 
    [ 2.500,  3.750) = 1608 
    [ 3.750,  5.000) = 109 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      2.023 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.826 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =     12.009 ms/op
     p(99.9900) =     12.238 ms/op
     p(99.9990) =     12.304 ms/op
     p(99.9999) =     12.304 ms/op
    p(100.0000) =     12.304 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.448 ±(99.9%) 0.155 ms/op
Iteration   1: 3.693 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   6.402 ms/op
                 listUser·p0.999:  9.880 ms/op
                 listUser·p0.9999: 10.748 ms/op
                 listUser·p1.00:   10.748 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8651
  mean =      3.693 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 66 
    [ 2.000,  3.000) = 1589 
    [ 3.000,  4.000) = 4297 
    [ 4.000,  5.000) = 2339 
    [ 5.000,  6.000) = 209 
    [ 6.000,  7.000) = 103 
    [ 7.000,  8.000) = 15 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      6.402 ms/op
     p(99.9000) =      9.880 ms/op
     p(99.9900) =     10.748 ms/op
     p(99.9990) =     10.748 ms/op
     p(99.9999) =     10.748 ms/op
    p(100.0000) =     10.748 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.944          ops/ms
ClientSimple.existUser                       thrpt         12.216          ops/ms
ClientSimple.getUser                         thrpt         13.363          ops/ms
ClientSimple.listUser                        thrpt          8.400          ops/ms
ClientSimple.createUser                       avgt          2.263           ms/op
ClientSimple.existUser                        avgt          1.951           ms/op
ClientSimple.getUser                          avgt          2.027           ms/op
ClientSimple.listUser                         avgt          3.108           ms/op
ClientSimple.createUser                     sample  14722   2.172 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.899           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.993           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.576           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.900           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.689           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.973           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.018           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.251           ms/op
ClientSimple.existUser                      sample  16924   1.889 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.578           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.720           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.417           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.662           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.810           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.665           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.241           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.990           ms/op
ClientSimple.getUser                        sample  15077   2.119 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.950           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.023           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.568           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.826           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.571           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.009           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.238           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.304           ms/op
ClientSimple.listUser                       sample   8651   3.693 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.055           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.707           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.841           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.402           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.880           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.748           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.748           ms/op

Benchmark result is saved to 1719317800250.json
