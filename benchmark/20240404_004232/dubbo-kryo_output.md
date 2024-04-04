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
# Warmup Iteration   1: 1.929 ops/ms
Iteration   1: 7.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.060 ops/ms


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
# Warmup Iteration   1: 6.410 ops/ms
Iteration   1: 14.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.706 ops/ms


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
# Warmup Iteration   1: 5.995 ops/ms
Iteration   1: 13.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.423 ops/ms


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
# Warmup Iteration   1: 5.432 ops/ms
Iteration   1: 8.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.735 ops/ms


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
# Warmup Iteration   1: 3.852 ±(99.9%) 0.077 ms/op
Iteration   1: 2.130 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.130 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.583 ±(99.9%) 0.063 ms/op
Iteration   1: 1.758 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.758 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.219 ±(99.9%) 0.056 ms/op
Iteration   1: 2.205 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.205 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.589 ±(99.9%) 0.088 ms/op
Iteration   1: 3.481 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.481 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.433 ±(99.9%) 0.083 ms/op
Iteration   1: 2.306 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   0.538 ms/op
                 createUser·p0.50:   2.082 ms/op
                 createUser·p0.90:   2.841 ms/op
                 createUser·p0.95:   3.145 ms/op
                 createUser·p0.99:   7.504 ms/op
                 createUser·p0.999:  28.348 ms/op
                 createUser·p0.9999: 29.734 ms/op
                 createUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13882
  mean =      2.306 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10690 
    [ 2.500,  5.000) = 2966 
    [ 5.000,  7.500) = 87 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      2.082 ms/op
     p(90.0000) =      2.841 ms/op
     p(95.0000) =      3.145 ms/op
     p(99.0000) =      7.504 ms/op
     p(99.9000) =     28.348 ms/op
     p(99.9900) =     29.734 ms/op
     p(99.9990) =     30.409 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


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
# Warmup Iteration   1: 2.840 ±(99.9%) 0.058 ms/op
Iteration   1: 2.051 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.775 ms/op
                 existUser·p0.50:   2.028 ms/op
                 existUser·p0.90:   2.503 ms/op
                 existUser·p0.95:   2.732 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  11.278 ms/op
                 existUser·p0.9999: 11.469 ms/op
                 existUser·p1.00:   11.534 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15658
  mean =      2.051 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 427 
    [ 1.250,  2.500) = 13657 
    [ 2.500,  3.750) = 1456 
    [ 3.750,  5.000) = 71 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      2.028 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.732 ms/op
     p(99.0000) =      3.498 ms/op
     p(99.9000) =     11.278 ms/op
     p(99.9900) =     11.469 ms/op
     p(99.9990) =     11.534 ms/op
     p(99.9999) =     11.534 ms/op
    p(100.0000) =     11.534 ms/op


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
# Warmup Iteration   1: 3.871 ±(99.9%) 0.144 ms/op
Iteration   1: 2.213 ±(99.9%) 0.049 ms/op
                 getUser·p0.00:   0.911 ms/op
                 getUser·p0.50:   2.075 ms/op
                 getUser·p0.90:   2.740 ms/op
                 getUser·p0.95:   2.945 ms/op
                 getUser·p0.99:   3.709 ms/op
                 getUser·p0.999:  37.445 ms/op
                 getUser·p0.9999: 38.273 ms/op
                 getUser·p1.00:   38.273 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14635
  mean =      2.213 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11980 
    [ 2.500,  5.000) = 2546 
    [ 5.000,  7.500) = 44 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      2.075 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      2.945 ms/op
     p(99.0000) =      3.709 ms/op
     p(99.9000) =     37.445 ms/op
     p(99.9900) =     38.273 ms/op
     p(99.9990) =     38.273 ms/op
     p(99.9999) =     38.273 ms/op
    p(100.0000) =     38.273 ms/op


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
# Warmup Iteration   1: 4.462 ±(99.9%) 0.120 ms/op
Iteration   1: 3.383 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   3.428 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.384 ms/op
                 listUser·p0.99:   5.038 ms/op
                 listUser·p0.999:  10.060 ms/op
                 listUser·p0.9999: 10.207 ms/op
                 listUser·p1.00:   10.207 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9456
  mean =      3.383 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 156 
    [ 2.000,  3.000) = 2910 
    [ 3.000,  4.000) = 4555 
    [ 4.000,  5.000) = 1723 
    [ 5.000,  6.000) = 70 
    [ 6.000,  7.000) = 7 
    [ 7.000,  8.000) = 1 
    [ 8.000,  9.000) = 1 
    [ 9.000, 10.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.384 ms/op
     p(99.0000) =      5.038 ms/op
     p(99.9000) =     10.060 ms/op
     p(99.9900) =     10.207 ms/op
     p(99.9990) =     10.207 ms/op
     p(99.9999) =     10.207 ms/op
    p(100.0000) =     10.207 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.060          ops/ms
ClientSimple.existUser                       thrpt         14.706          ops/ms
ClientSimple.getUser                         thrpt         13.423          ops/ms
ClientSimple.listUser                        thrpt          8.735          ops/ms
ClientSimple.createUser                       avgt          2.130           ms/op
ClientSimple.existUser                        avgt          1.758           ms/op
ClientSimple.getUser                          avgt          2.205           ms/op
ClientSimple.listUser                         avgt          3.481           ms/op
ClientSimple.createUser                     sample  13882   2.306 ± 0.051   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.538           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.082           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.841           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.145           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.504           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.348           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.734           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.409           ms/op
ClientSimple.existUser                      sample  15658   2.051 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.775           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.028           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.503           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.732           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.498           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.278           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.469           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.534           ms/op
ClientSimple.getUser                        sample  14635   2.213 ± 0.049   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.911           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.075           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.740           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.945           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.709           ms/op
ClientSimple.getUser:getUser·p0.999         sample         37.445           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         38.273           ms/op
ClientSimple.getUser:getUser·p1.00          sample         38.273           ms/op
ClientSimple.listUser                       sample   9456   3.383 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.890           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.428           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.384           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.038           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.060           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.207           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.207           ms/op

Benchmark result is saved to 1712191109303.json
