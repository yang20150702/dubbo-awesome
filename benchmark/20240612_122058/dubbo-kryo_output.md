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
# Warmup Iteration   1: 1.800 ops/ms
Iteration   1: 6.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.366 ops/ms


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
# Warmup Iteration   1: 5.766 ops/ms
Iteration   1: 11.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.917 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.926 ops/ms
Iteration   1: 12.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.114 ops/ms


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
# Warmup Iteration   1: 4.142 ops/ms
Iteration   1: 8.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.179 ops/ms


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
# Warmup Iteration   1: 3.633 ±(99.9%) 0.074 ms/op
Iteration   1: 2.108 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.108 ms/op


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
# Warmup Iteration   1: 3.490 ±(99.9%) 0.083 ms/op
Iteration   1: 1.768 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.768 ms/op


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
# Warmup Iteration   1: 3.365 ±(99.9%) 0.069 ms/op
Iteration   1: 2.037 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.037 ms/op


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
# Warmup Iteration   1: 5.034 ±(99.9%) 0.102 ms/op
Iteration   1: 3.383 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.383 ms/op


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
# Warmup Iteration   1: 3.624 ±(99.9%) 0.086 ms/op
Iteration   1: 2.192 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.690 ms/op
                 createUser·p0.50:   2.021 ms/op
                 createUser·p0.90:   2.700 ms/op
                 createUser·p0.95:   3.056 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  20.087 ms/op
                 createUser·p0.9999: 22.100 ms/op
                 createUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14557
  mean =      2.192 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12056 
    [ 2.500,  5.000) = 2305 
    [ 5.000,  7.500) = 101 
    [ 7.500, 10.000) = 48 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      2.021 ms/op
     p(90.0000) =      2.700 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     20.087 ms/op
     p(99.9900) =     22.100 ms/op
     p(99.9990) =     22.249 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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
# Warmup Iteration   1: 2.787 ±(99.9%) 0.073 ms/op
Iteration   1: 1.895 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   1.743 ms/op
                 existUser·p0.90:   2.302 ms/op
                 existUser·p0.95:   2.474 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  26.608 ms/op
                 existUser·p0.9999: 27.132 ms/op
                 existUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16987
  mean =      1.895 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16220 
    [ 2.500,  5.000) = 634 
    [ 5.000,  7.500) = 69 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      1.743 ms/op
     p(90.0000) =      2.302 ms/op
     p(95.0000) =      2.474 ms/op
     p(99.0000) =      4.170 ms/op
     p(99.9000) =     26.608 ms/op
     p(99.9900) =     27.132 ms/op
     p(99.9990) =     27.132 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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
# Warmup Iteration   1: 3.265 ±(99.9%) 0.097 ms/op
Iteration   1: 2.090 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.639 ms/op
                 getUser·p0.50:   1.991 ms/op
                 getUser·p0.90:   2.662 ms/op
                 getUser·p0.95:   2.830 ms/op
                 getUser·p0.99:   3.588 ms/op
                 getUser·p0.999:  16.068 ms/op
                 getUser·p0.9999: 16.972 ms/op
                 getUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15310
  mean =      2.090 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 175 
    [ 1.250,  2.500) = 12605 
    [ 2.500,  3.750) = 2438 
    [ 3.750,  5.000) = 55 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      1.991 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.830 ms/op
     p(99.0000) =      3.588 ms/op
     p(99.9000) =     16.068 ms/op
     p(99.9900) =     16.972 ms/op
     p(99.9990) =     17.007 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 4.973 ±(99.9%) 0.141 ms/op
Iteration   1: 3.440 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.298 ms/op
                 listUser·p0.50:   3.379 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  13.763 ms/op
                 listUser·p0.9999: 13.976 ms/op
                 listUser·p1.00:   13.976 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9309
  mean =      3.440 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 856 
    [ 2.500,  3.750) = 5578 
    [ 3.750,  5.000) = 2600 
    [ 5.000,  6.250) = 155 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     13.763 ms/op
     p(99.9900) =     13.976 ms/op
     p(99.9990) =     13.976 ms/op
     p(99.9999) =     13.976 ms/op
    p(100.0000) =     13.976 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.366          ops/ms
ClientSimple.existUser                       thrpt         11.917          ops/ms
ClientSimple.getUser                         thrpt         12.114          ops/ms
ClientSimple.listUser                        thrpt          8.179          ops/ms
ClientSimple.createUser                       avgt          2.108           ms/op
ClientSimple.existUser                        avgt          1.768           ms/op
ClientSimple.getUser                          avgt          2.037           ms/op
ClientSimple.listUser                         avgt          3.383           ms/op
ClientSimple.createUser                     sample  14557   2.192 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.690           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.021           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.700           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.056           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.095           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.087           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.100           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.249           ms/op
ClientSimple.existUser                      sample  16987   1.895 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.781           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.743           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.302           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.474           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.170           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.608           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.132           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.132           ms/op
ClientSimple.getUser                        sample  15310   2.090 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.639           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.991           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.662           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.830           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.588           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.068           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.972           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.007           ms/op
ClientSimple.listUser                       sample   9309   3.440 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.298           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.379           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.628           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.472           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.763           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.976           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.976           ms/op

Benchmark result is saved to 1718194605118.json
