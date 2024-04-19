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
# Warmup Iteration   1: 1.767 ops/ms
Iteration   1: 6.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.575 ops/ms


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
# Warmup Iteration   1: 5.945 ops/ms
Iteration   1: 12.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.412 ops/ms


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
# Warmup Iteration   1: 5.678 ops/ms
Iteration   1: 12.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.894 ops/ms


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
# Warmup Iteration   1: 5.600 ops/ms
Iteration   1: 9.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.131 ops/ms


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
# Warmup Iteration   1: 3.848 ±(99.9%) 0.073 ms/op
Iteration   1: 2.221 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.221 ms/op


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
# Warmup Iteration   1: 3.124 ±(99.9%) 0.050 ms/op
Iteration   1: 1.925 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.925 ms/op


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
# Warmup Iteration   1: 3.327 ±(99.9%) 0.053 ms/op
Iteration   1: 2.150 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.150 ms/op


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
# Warmup Iteration   1: 4.418 ±(99.9%) 0.097 ms/op
Iteration   1: 3.078 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.078 ms/op


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
# Warmup Iteration   1: 3.161 ±(99.9%) 0.079 ms/op
Iteration   1: 2.245 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.372 ms/op
                 createUser·p0.50:   2.101 ms/op
                 createUser·p0.90:   2.814 ms/op
                 createUser·p0.95:   3.047 ms/op
                 createUser·p0.99:   6.129 ms/op
                 createUser·p0.999:  32.236 ms/op
                 createUser·p0.9999: 34.419 ms/op
                 createUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14232
  mean =      2.245 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11575 
    [ 2.500,  5.000) = 2488 
    [ 5.000,  7.500) = 69 
    [ 7.500, 10.000) = 68 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.372 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.814 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      6.129 ms/op
     p(99.9000) =     32.236 ms/op
     p(99.9900) =     34.419 ms/op
     p(99.9990) =     34.669 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


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
# Warmup Iteration   1: 2.831 ±(99.9%) 0.061 ms/op
Iteration   1: 2.108 ±(99.9%) 0.048 ms/op
                 existUser·p0.00:   0.308 ms/op
                 existUser·p0.50:   1.966 ms/op
                 existUser·p0.90:   2.531 ms/op
                 existUser·p0.95:   2.757 ms/op
                 existUser·p0.99:   4.112 ms/op
                 existUser·p0.999:  30.999 ms/op
                 existUser·p0.9999: 31.749 ms/op
                 existUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15159
  mean =      2.108 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13530 
    [ 2.500,  5.000) = 1520 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.308 ms/op
     p(50.0000) =      1.966 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      4.112 ms/op
     p(99.9000) =     30.999 ms/op
     p(99.9900) =     31.749 ms/op
     p(99.9990) =     31.850 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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
# Warmup Iteration   1: 3.749 ±(99.9%) 0.202 ms/op
Iteration   1: 2.216 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   2.126 ms/op
                 getUser·p0.90:   2.720 ms/op
                 getUser·p0.95:   2.945 ms/op
                 getUser·p0.99:   4.258 ms/op
                 getUser·p0.999:  16.523 ms/op
                 getUser·p0.9999: 19.852 ms/op
                 getUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14531
  mean =      2.216 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 261 
    [ 1.250,  2.500) = 11179 
    [ 2.500,  3.750) = 2835 
    [ 3.750,  5.000) = 174 
    [ 5.000,  6.250) = 28 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      2.126 ms/op
     p(90.0000) =      2.720 ms/op
     p(95.0000) =      2.945 ms/op
     p(99.0000) =      4.258 ms/op
     p(99.9000) =     16.523 ms/op
     p(99.9900) =     19.852 ms/op
     p(99.9990) =     19.956 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 4.429 ±(99.9%) 0.113 ms/op
Iteration   1: 3.430 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   1.014 ms/op
                 listUser·p0.50:   3.232 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.316 ms/op
                 listUser·p0.999:  16.482 ms/op
                 listUser·p0.9999: 18.350 ms/op
                 listUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9330
  mean =      3.430 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 241 
    [ 2.500,  3.750) = 6684 
    [ 3.750,  5.000) = 2206 
    [ 5.000,  6.250) = 96 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     16.482 ms/op
     p(99.9900) =     18.350 ms/op
     p(99.9990) =     18.350 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.575          ops/ms
ClientSimple.existUser                       thrpt         12.412          ops/ms
ClientSimple.getUser                         thrpt         12.894          ops/ms
ClientSimple.listUser                        thrpt          9.131          ops/ms
ClientSimple.createUser                       avgt          2.221           ms/op
ClientSimple.existUser                        avgt          1.925           ms/op
ClientSimple.getUser                          avgt          2.150           ms/op
ClientSimple.listUser                         avgt          3.078           ms/op
ClientSimple.createUser                     sample  14232   2.245 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.372           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.101           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.814           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.047           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.129           ms/op
ClientSimple.createUser:createUser·p0.999   sample         32.236           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         34.419           ms/op
ClientSimple.createUser:createUser·p1.00    sample         34.669           ms/op
ClientSimple.existUser                      sample  15159   2.108 ± 0.048   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.308           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.966           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.531           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.757           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.112           ms/op
ClientSimple.existUser:existUser·p0.999     sample         30.999           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         31.749           ms/op
ClientSimple.existUser:existUser·p1.00      sample         31.850           ms/op
ClientSimple.getUser                        sample  14531   2.216 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.709           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.126           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.720           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.945           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.258           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.523           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.852           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.956           ms/op
ClientSimple.listUser                       sample   9330   3.430 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.014           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.232           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.182           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.316           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.482           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.350           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.350           ms/op

Benchmark result is saved to 1713487058391.json
