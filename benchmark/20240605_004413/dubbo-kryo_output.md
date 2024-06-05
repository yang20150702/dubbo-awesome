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
# Warmup Iteration   1: 1.782 ops/ms
Iteration   1: 7.339 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.339 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.797 ops/ms
Iteration   1: 11.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.048 ops/ms


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
# Warmup Iteration   1: 4.997 ops/ms
Iteration   1: 12.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.691 ops/ms


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
# Warmup Iteration   1: 5.385 ops/ms
Iteration   1: 8.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.816 ops/ms


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
# Warmup Iteration   1: 4.431 ±(99.9%) 0.091 ms/op
Iteration   1: 2.147 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.147 ms/op


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
# Warmup Iteration   1: 3.017 ±(99.9%) 0.052 ms/op
Iteration   1: 1.695 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.695 ms/op


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
# Warmup Iteration   1: 3.277 ±(99.9%) 0.070 ms/op
Iteration   1: 2.018 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.018 ms/op


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
# Warmup Iteration   1: 4.370 ±(99.9%) 0.090 ms/op
Iteration   1: 3.437 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.437 ms/op


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
# Warmup Iteration   1: 3.557 ±(99.9%) 0.090 ms/op
Iteration   1: 2.400 ±(99.9%) 0.059 ms/op
                 createUser·p0.00:   0.421 ms/op
                 createUser·p0.50:   2.195 ms/op
                 createUser·p0.90:   2.937 ms/op
                 createUser·p0.95:   3.334 ms/op
                 createUser·p0.99:   9.634 ms/op
                 createUser·p0.999:  37.028 ms/op
                 createUser·p0.9999: 39.651 ms/op
                 createUser·p1.00:   40.042 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13314
  mean =      2.400 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13043 
    [ 5.000, 10.000) = 159 
    [10.000, 15.000) = 48 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.421 ms/op
     p(50.0000) =      2.195 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.334 ms/op
     p(99.0000) =      9.634 ms/op
     p(99.9000) =     37.028 ms/op
     p(99.9900) =     39.651 ms/op
     p(99.9990) =     40.042 ms/op
     p(99.9999) =     40.042 ms/op
    p(100.0000) =     40.042 ms/op


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
# Warmup Iteration   1: 3.060 ±(99.9%) 0.075 ms/op
Iteration   1: 2.121 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   2.114 ms/op
                 existUser·p0.90:   2.589 ms/op
                 existUser·p0.95:   2.793 ms/op
                 existUser·p0.99:   4.969 ms/op
                 existUser·p0.999:  11.512 ms/op
                 existUser·p0.9999: 11.675 ms/op
                 existUser·p1.00:   11.780 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15342
  mean =      2.121 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 169 
    [ 1.250,  2.500) = 13100 
    [ 2.500,  3.750) = 1869 
    [ 3.750,  5.000) = 63 
    [ 5.000,  6.250) = 104 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      2.114 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.793 ms/op
     p(99.0000) =      4.969 ms/op
     p(99.9000) =     11.512 ms/op
     p(99.9900) =     11.675 ms/op
     p(99.9990) =     11.780 ms/op
     p(99.9999) =     11.780 ms/op
    p(100.0000) =     11.780 ms/op


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
# Warmup Iteration   1: 3.369 ±(99.9%) 0.090 ms/op
Iteration   1: 2.232 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.436 ms/op
                 getUser·p0.50:   2.093 ms/op
                 getUser·p0.90:   2.769 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.899 ms/op
                 getUser·p0.999:  20.906 ms/op
                 getUser·p0.9999: 21.023 ms/op
                 getUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14318
  mean =      2.232 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11419 
    [ 2.500,  5.000) = 2835 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.436 ms/op
     p(50.0000) =      2.093 ms/op
     p(90.0000) =      2.769 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =     20.906 ms/op
     p(99.9900) =     21.023 ms/op
     p(99.9990) =     21.037 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


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
# Warmup Iteration   1: 4.912 ±(99.9%) 0.144 ms/op
Iteration   1: 3.246 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.228 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  13.238 ms/op
                 listUser·p0.9999: 13.418 ms/op
                 listUser·p1.00:   13.418 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9876
  mean =      3.246 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 2831 
    [ 2.500,  3.750) = 4313 
    [ 3.750,  5.000) = 2472 
    [ 5.000,  6.250) = 214 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     13.238 ms/op
     p(99.9900) =     13.418 ms/op
     p(99.9990) =     13.418 ms/op
     p(99.9999) =     13.418 ms/op
    p(100.0000) =     13.418 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.339          ops/ms
ClientSimple.existUser                       thrpt         11.048          ops/ms
ClientSimple.getUser                         thrpt         12.691          ops/ms
ClientSimple.listUser                        thrpt          8.816          ops/ms
ClientSimple.createUser                       avgt          2.147           ms/op
ClientSimple.existUser                        avgt          1.695           ms/op
ClientSimple.getUser                          avgt          2.018           ms/op
ClientSimple.listUser                         avgt          3.437           ms/op
ClientSimple.createUser                     sample  13314   2.400 ± 0.059   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.421           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.195           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.937           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.334           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.634           ms/op
ClientSimple.createUser:createUser·p0.999   sample         37.028           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         39.651           ms/op
ClientSimple.createUser:createUser·p1.00    sample         40.042           ms/op
ClientSimple.existUser                      sample  15342   2.121 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.765           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.114           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.589           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.793           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.969           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.512           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.675           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.780           ms/op
ClientSimple.getUser                        sample  14318   2.232 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.436           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.093           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.769           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.109           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.899           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.906           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.023           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.037           ms/op
ClientSimple.listUser                       sample   9876   3.246 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.176           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.228           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.645           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.546           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.238           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.418           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.418           ms/op

Benchmark result is saved to 1717548006380.json
