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
# Warmup Iteration   1: 1.940 ops/ms
Iteration   1: 6.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.875 ops/ms


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
# Warmup Iteration   1: 5.879 ops/ms
Iteration   1: 12.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.036 ops/ms


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
# Warmup Iteration   1: 6.938 ops/ms
Iteration   1: 11.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.719 ops/ms


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
# Warmup Iteration   1: 4.471 ops/ms
Iteration   1: 8.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.697 ops/ms


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
# Warmup Iteration   1: 4.043 ±(99.9%) 0.072 ms/op
Iteration   1: 2.220 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.220 ms/op


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
# Warmup Iteration   1: 3.657 ±(99.9%) 0.060 ms/op
Iteration   1: 1.930 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.930 ms/op


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
# Warmup Iteration   1: 3.208 ±(99.9%) 0.054 ms/op
Iteration   1: 1.984 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.984 ms/op


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
# Warmup Iteration   1: 4.124 ±(99.9%) 0.088 ms/op
Iteration   1: 3.170 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.170 ms/op


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
# Warmup Iteration   1: 3.809 ±(99.9%) 0.103 ms/op
Iteration   1: 2.480 ±(99.9%) 0.050 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   2.195 ms/op
                 createUser·p0.90:   3.195 ms/op
                 createUser·p0.95:   3.445 ms/op
                 createUser·p0.99:   8.782 ms/op
                 createUser·p0.999:  27.660 ms/op
                 createUser·p0.9999: 28.124 ms/op
                 createUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12875
  mean =      2.480 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9201 
    [ 2.500,  5.000) = 3449 
    [ 5.000,  7.500) = 53 
    [ 7.500, 10.000) = 45 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      2.195 ms/op
     p(90.0000) =      3.195 ms/op
     p(95.0000) =      3.445 ms/op
     p(99.0000) =      8.782 ms/op
     p(99.9000) =     27.660 ms/op
     p(99.9900) =     28.124 ms/op
     p(99.9990) =     28.180 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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
# Warmup Iteration   1: 2.822 ±(99.9%) 0.058 ms/op
Iteration   1: 1.973 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.349 ms/op
                 existUser·p0.50:   1.919 ms/op
                 existUser·p0.90:   2.474 ms/op
                 existUser·p0.95:   2.720 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  11.514 ms/op
                 existUser·p0.9999: 12.968 ms/op
                 existUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16213
  mean =      1.973 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 912 
    [ 1.250,  2.500) = 13841 
    [ 2.500,  3.750) = 1249 
    [ 3.750,  5.000) = 90 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.349 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =     11.514 ms/op
     p(99.9900) =     12.968 ms/op
     p(99.9990) =     13.009 ms/op
     p(99.9999) =     13.009 ms/op
    p(100.0000) =     13.009 ms/op


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
# Warmup Iteration   1: 3.216 ±(99.9%) 0.075 ms/op
Iteration   1: 1.975 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   1.821 ms/op
                 getUser·p0.90:   2.454 ms/op
                 getUser·p0.95:   2.613 ms/op
                 getUser·p0.99:   3.379 ms/op
                 getUser·p0.999:  19.923 ms/op
                 getUser·p0.9999: 20.276 ms/op
                 getUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16189
  mean =      1.975 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14870 
    [ 2.500,  5.000) = 1241 
    [ 5.000,  7.500) = 12 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.454 ms/op
     p(95.0000) =      2.613 ms/op
     p(99.0000) =      3.379 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     20.276 ms/op
     p(99.9990) =     20.316 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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
# Warmup Iteration   1: 4.339 ±(99.9%) 0.111 ms/op
Iteration   1: 3.303 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   0.594 ms/op
                 listUser·p0.50:   3.047 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   6.413 ms/op
                 listUser·p0.999:  21.463 ms/op
                 listUser·p0.9999: 21.627 ms/op
                 listUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9706
  mean =      3.303 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 954 
    [ 2.500,  5.000) = 8495 
    [ 5.000,  7.500) = 219 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.413 ms/op
     p(99.9000) =     21.463 ms/op
     p(99.9900) =     21.627 ms/op
     p(99.9990) =     21.627 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.875          ops/ms
ClientSimple.existUser                       thrpt         12.036          ops/ms
ClientSimple.getUser                         thrpt         11.719          ops/ms
ClientSimple.listUser                        thrpt          8.697          ops/ms
ClientSimple.createUser                       avgt          2.220           ms/op
ClientSimple.existUser                        avgt          1.930           ms/op
ClientSimple.getUser                          avgt          1.984           ms/op
ClientSimple.listUser                         avgt          3.170           ms/op
ClientSimple.createUser                     sample  12875   2.480 ± 0.050   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.746           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.195           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.195           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.445           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.782           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.660           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.124           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.180           ms/op
ClientSimple.existUser                      sample  16213   1.973 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.349           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.919           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.474           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.720           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.243           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.514           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.968           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.009           ms/op
ClientSimple.getUser                        sample  16189   1.975 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.733           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.821           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.454           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.613           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.379           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.923           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.276           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.316           ms/op
ClientSimple.listUser                       sample   9706   3.303 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.594           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.047           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.243           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.413           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.463           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.627           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.627           ms/op

Benchmark result is saved to 1720181784049.json
