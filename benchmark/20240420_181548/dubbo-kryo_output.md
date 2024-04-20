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
# Warmup Iteration   1: 1.816 ops/ms
Iteration   1: 6.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.935 ops/ms


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
# Warmup Iteration   1: 5.593 ops/ms
Iteration   1: 12.172 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.172 ops/ms


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
# Warmup Iteration   1: 5.977 ops/ms
Iteration   1: 12.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.710 ops/ms


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
# Warmup Iteration   1: 5.116 ops/ms
Iteration   1: 9.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.115 ops/ms


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
# Warmup Iteration   1: 4.034 ±(99.9%) 0.080 ms/op
Iteration   1: 2.287 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.287 ms/op


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
# Warmup Iteration   1: 3.250 ±(99.9%) 0.050 ms/op
Iteration   1: 2.030 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 2.989 ±(99.9%) 0.070 ms/op
Iteration   1: 2.018 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.018 ms/op


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
# Warmup Iteration   1: 4.287 ±(99.9%) 0.083 ms/op
Iteration   1: 3.867 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.867 ms/op


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
# Warmup Iteration   1: 3.728 ±(99.9%) 0.101 ms/op
Iteration   1: 2.196 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.699 ms/op
                 createUser·p0.50:   2.011 ms/op
                 createUser·p0.90:   2.732 ms/op
                 createUser·p0.95:   2.982 ms/op
                 createUser·p0.99:   9.015 ms/op
                 createUser·p0.999:  12.927 ms/op
                 createUser·p0.9999: 13.273 ms/op
                 createUser·p1.00:   13.287 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14495
  mean =      2.196 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 11321 
    [ 2.500,  3.750) = 2801 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 20 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      2.011 ms/op
     p(90.0000) =      2.732 ms/op
     p(95.0000) =      2.982 ms/op
     p(99.0000) =      9.015 ms/op
     p(99.9000) =     12.927 ms/op
     p(99.9900) =     13.273 ms/op
     p(99.9990) =     13.287 ms/op
     p(99.9999) =     13.287 ms/op
    p(100.0000) =     13.287 ms/op


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
# Warmup Iteration   1: 2.720 ±(99.9%) 0.061 ms/op
Iteration   1: 1.705 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.357 ms/op
                 existUser·p0.50:   1.628 ms/op
                 existUser·p0.90:   1.923 ms/op
                 existUser·p0.95:   2.118 ms/op
                 existUser·p0.99:   2.642 ms/op
                 existUser·p0.999:  20.218 ms/op
                 existUser·p0.9999: 20.779 ms/op
                 existUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18722
  mean =      1.705 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18471 
    [ 2.500,  5.000) = 187 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.357 ms/op
     p(50.0000) =      1.628 ms/op
     p(90.0000) =      1.923 ms/op
     p(95.0000) =      2.118 ms/op
     p(99.0000) =      2.642 ms/op
     p(99.9000) =     20.218 ms/op
     p(99.9900) =     20.779 ms/op
     p(99.9990) =     20.808 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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
# Warmup Iteration   1: 3.245 ±(99.9%) 0.092 ms/op
Iteration   1: 1.940 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.515 ms/op
                 getUser·p0.50:   1.806 ms/op
                 getUser·p0.90:   2.421 ms/op
                 getUser·p0.95:   2.617 ms/op
                 getUser·p0.99:   3.597 ms/op
                 getUser·p0.999:  12.812 ms/op
                 getUser·p0.9999: 13.229 ms/op
                 getUser·p1.00:   13.271 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16474
  mean =      1.940 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 196 
    [ 1.250,  2.500) = 15120 
    [ 2.500,  3.750) = 1014 
    [ 3.750,  5.000) = 74 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.617 ms/op
     p(99.0000) =      3.597 ms/op
     p(99.9000) =     12.812 ms/op
     p(99.9900) =     13.229 ms/op
     p(99.9990) =     13.271 ms/op
     p(99.9999) =     13.271 ms/op
    p(100.0000) =     13.271 ms/op


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
# Warmup Iteration   1: 5.155 ±(99.9%) 0.135 ms/op
Iteration   1: 3.491 ±(99.9%) 0.056 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.465 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.550 ms/op
                 listUser·p0.999:  24.204 ms/op
                 listUser·p0.9999: 27.951 ms/op
                 listUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9179
  mean =      3.491 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1572 
    [ 2.500,  5.000) = 7341 
    [ 5.000,  7.500) = 187 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.550 ms/op
     p(99.9000) =     24.204 ms/op
     p(99.9900) =     27.951 ms/op
     p(99.9990) =     27.951 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.935          ops/ms
ClientSimple.existUser                       thrpt         12.172          ops/ms
ClientSimple.getUser                         thrpt         12.710          ops/ms
ClientSimple.listUser                        thrpt          9.115          ops/ms
ClientSimple.createUser                       avgt          2.287           ms/op
ClientSimple.existUser                        avgt          2.030           ms/op
ClientSimple.getUser                          avgt          2.018           ms/op
ClientSimple.listUser                         avgt          3.867           ms/op
ClientSimple.createUser                     sample  14495   2.196 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.699           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.011           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.732           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.982           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.015           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.927           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.273           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.287           ms/op
ClientSimple.existUser                      sample  18722   1.705 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.357           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.628           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.923           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.118           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.642           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.218           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.779           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.808           ms/op
ClientSimple.getUser                        sample  16474   1.940 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.515           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.806           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.421           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.617           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.597           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.812           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.229           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.271           ms/op
ClientSimple.listUser                       sample   9179   3.491 ± 0.056   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.067           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.465           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.579           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.550           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.204           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         27.951           ms/op
ClientSimple.listUser:listUser·p1.00        sample         27.951           ms/op

Benchmark result is saved to 1713636691790.json
