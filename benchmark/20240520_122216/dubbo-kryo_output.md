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
# Warmup Iteration   1: 1.872 ops/ms
Iteration   1: 7.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.825 ops/ms


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
# Warmup Iteration   1: 7.175 ops/ms
Iteration   1: 12.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.125 ops/ms


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
# Warmup Iteration   1: 6.185 ops/ms
Iteration   1: 12.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.982 ops/ms


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
# Warmup Iteration   1: 5.443 ops/ms
Iteration   1: 8.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.927 ops/ms


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
# Warmup Iteration   1: 3.689 ±(99.9%) 0.079 ms/op
Iteration   1: 2.239 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.239 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.658 ±(99.9%) 0.091 ms/op
Iteration   1: 1.825 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.825 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.670 ±(99.9%) 0.068 ms/op
Iteration   1: 1.970 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.970 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.135 ±(99.9%) 0.080 ms/op
Iteration   1: 3.290 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.290 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.656 ±(99.9%) 0.105 ms/op
Iteration   1: 2.309 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   2.159 ms/op
                 createUser·p0.90:   2.822 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  20.349 ms/op
                 createUser·p0.9999: 21.194 ms/op
                 createUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13996
  mean =      2.309 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10349 
    [ 2.500,  5.000) = 3443 
    [ 5.000,  7.500) = 138 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      2.159 ms/op
     p(90.0000) =      2.822 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     20.349 ms/op
     p(99.9900) =     21.194 ms/op
     p(99.9990) =     21.234 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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
# Warmup Iteration   1: 3.077 ±(99.9%) 0.071 ms/op
Iteration   1: 1.749 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.698 ms/op
                 existUser·p0.50:   1.634 ms/op
                 existUser·p0.90:   2.118 ms/op
                 existUser·p0.95:   2.273 ms/op
                 existUser·p0.99:   2.746 ms/op
                 existUser·p0.999:  15.860 ms/op
                 existUser·p0.9999: 19.527 ms/op
                 existUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18387
  mean =      1.749 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18007 
    [ 2.500,  5.000) = 308 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      1.634 ms/op
     p(90.0000) =      2.118 ms/op
     p(95.0000) =      2.273 ms/op
     p(99.0000) =      2.746 ms/op
     p(99.9000) =     15.860 ms/op
     p(99.9900) =     19.527 ms/op
     p(99.9990) =     20.709 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 3.360 ±(99.9%) 0.095 ms/op
Iteration   1: 2.136 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.572 ms/op
                 getUser·p0.50:   2.030 ms/op
                 getUser·p0.90:   2.793 ms/op
                 getUser·p0.95:   2.994 ms/op
                 getUser·p0.99:   3.973 ms/op
                 getUser·p0.999:  13.009 ms/op
                 getUser·p0.9999: 13.599 ms/op
                 getUser·p1.00:   14.074 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14993
  mean =      2.136 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 865 
    [ 1.250,  2.500) = 10919 
    [ 2.500,  3.750) = 3027 
    [ 3.750,  5.000) = 81 
    [ 5.000,  6.250) = 69 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      2.030 ms/op
     p(90.0000) =      2.793 ms/op
     p(95.0000) =      2.994 ms/op
     p(99.0000) =      3.973 ms/op
     p(99.9000) =     13.009 ms/op
     p(99.9900) =     13.599 ms/op
     p(99.9990) =     14.074 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


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
# Warmup Iteration   1: 4.956 ±(99.9%) 0.130 ms/op
Iteration   1: 3.662 ±(99.9%) 0.076 ms/op
                 listUser·p0.00:   1.276 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   8.782 ms/op
                 listUser·p0.999:  34.285 ms/op
                 listUser·p0.9999: 34.931 ms/op
                 listUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8712
  mean =      3.662 ±(99.9%) 0.076 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 986 
    [ 2.500,  5.000) = 7472 
    [ 5.000,  7.500) = 160 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      8.782 ms/op
     p(99.9000) =     34.285 ms/op
     p(99.9900) =     34.931 ms/op
     p(99.9990) =     34.931 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.825          ops/ms
ClientSimple.existUser                       thrpt         12.125          ops/ms
ClientSimple.getUser                         thrpt         12.982          ops/ms
ClientSimple.listUser                        thrpt          8.927          ops/ms
ClientSimple.createUser                       avgt          2.239           ms/op
ClientSimple.existUser                        avgt          1.825           ms/op
ClientSimple.getUser                          avgt          1.970           ms/op
ClientSimple.listUser                         avgt          3.290           ms/op
ClientSimple.createUser                     sample  13996   2.309 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.817           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.159           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.822           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.097           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.374           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.349           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.194           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.234           ms/op
ClientSimple.existUser                      sample  18387   1.749 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.698           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.634           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.118           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.273           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.746           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.860           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.527           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.709           ms/op
ClientSimple.getUser                        sample  14993   2.136 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.572           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.030           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.793           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.994           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.973           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.009           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.599           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.074           ms/op
ClientSimple.listUser                       sample   8712   3.662 ± 0.076   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.276           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.568           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.620           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.782           ms/op
ClientSimple.listUser:listUser·p0.999       sample         34.285           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         34.931           ms/op
ClientSimple.listUser:listUser·p1.00        sample         34.931           ms/op

Benchmark result is saved to 1716207484923.json
