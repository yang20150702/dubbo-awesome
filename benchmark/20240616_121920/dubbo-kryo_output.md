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
# Warmup Iteration   1: 2.015 ops/ms
Iteration   1: 8.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.366 ops/ms


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
# Warmup Iteration   1: 6.398 ops/ms
Iteration   1: 12.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.151 ops/ms


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
# Warmup Iteration   1: 6.780 ops/ms
Iteration   1: 12.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.475 ops/ms


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
# Warmup Iteration   1: 5.306 ops/ms
Iteration   1: 8.348 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.348 ops/ms


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
# Warmup Iteration   1: 4.209 ±(99.9%) 0.076 ms/op
Iteration   1: 2.343 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.343 ms/op


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
# Warmup Iteration   1: 3.264 ±(99.9%) 0.063 ms/op
Iteration   1: 1.877 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.877 ms/op


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
# Warmup Iteration   1: 3.356 ±(99.9%) 0.056 ms/op
Iteration   1: 1.943 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.943 ms/op


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
# Warmup Iteration   1: 5.180 ±(99.9%) 0.104 ms/op
Iteration   1: 4.033 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.033 ms/op


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
# Warmup Iteration   1: 3.330 ±(99.9%) 0.089 ms/op
Iteration   1: 2.256 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.302 ms/op
                 createUser·p0.50:   2.087 ms/op
                 createUser·p0.90:   2.740 ms/op
                 createUser·p0.95:   2.957 ms/op
                 createUser·p0.99:   4.907 ms/op
                 createUser·p0.999:  30.588 ms/op
                 createUser·p0.9999: 31.214 ms/op
                 createUser·p1.00:   31.228 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14172
  mean =      2.256 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11257 
    [ 2.500,  5.000) = 2786 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.302 ms/op
     p(50.0000) =      2.087 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      2.957 ms/op
     p(99.0000) =      4.907 ms/op
     p(99.9000) =     30.588 ms/op
     p(99.9900) =     31.214 ms/op
     p(99.9990) =     31.228 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


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
# Warmup Iteration   1: 3.223 ±(99.9%) 0.073 ms/op
Iteration   1: 1.953 ±(99.9%) 0.039 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   1.800 ms/op
                 existUser·p0.90:   2.228 ms/op
                 existUser·p0.95:   2.359 ms/op
                 existUser·p0.99:   3.203 ms/op
                 existUser·p0.999:  31.417 ms/op
                 existUser·p0.9999: 36.038 ms/op
                 existUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16371
  mean =      1.953 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15881 
    [ 2.500,  5.000) = 396 
    [ 5.000,  7.500) = 30 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      1.800 ms/op
     p(90.0000) =      2.228 ms/op
     p(95.0000) =      2.359 ms/op
     p(99.0000) =      3.203 ms/op
     p(99.9000) =     31.417 ms/op
     p(99.9900) =     36.038 ms/op
     p(99.9990) =     36.372 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


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
# Warmup Iteration   1: 3.194 ±(99.9%) 0.078 ms/op
Iteration   1: 2.007 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.633 ms/op
                 getUser·p0.50:   1.872 ms/op
                 getUser·p0.90:   2.436 ms/op
                 getUser·p0.95:   2.662 ms/op
                 getUser·p0.99:   4.478 ms/op
                 getUser·p0.999:  25.266 ms/op
                 getUser·p0.9999: 25.553 ms/op
                 getUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15932
  mean =      2.007 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14591 
    [ 2.500,  5.000) = 1226 
    [ 5.000,  7.500) = 81 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      1.872 ms/op
     p(90.0000) =      2.436 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =      4.478 ms/op
     p(99.9000) =     25.266 ms/op
     p(99.9900) =     25.553 ms/op
     p(99.9990) =     25.592 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 4.428 ±(99.9%) 0.131 ms/op
Iteration   1: 3.202 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.142 ms/op
                 listUser·p0.999:  13.401 ms/op
                 listUser·p0.9999: 14.746 ms/op
                 listUser·p1.00:   14.746 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9927
  mean =      3.202 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1615 
    [ 2.500,  3.750) = 5621 
    [ 3.750,  5.000) = 2544 
    [ 5.000,  6.250) = 120 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.142 ms/op
     p(99.9000) =     13.401 ms/op
     p(99.9900) =     14.746 ms/op
     p(99.9990) =     14.746 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.366          ops/ms
ClientSimple.existUser                       thrpt         12.151          ops/ms
ClientSimple.getUser                         thrpt         12.475          ops/ms
ClientSimple.listUser                        thrpt          8.348          ops/ms
ClientSimple.createUser                       avgt          2.343           ms/op
ClientSimple.existUser                        avgt          1.877           ms/op
ClientSimple.getUser                          avgt          1.943           ms/op
ClientSimple.listUser                         avgt          4.033           ms/op
ClientSimple.createUser                     sample  14172   2.256 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.302           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.087           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.740           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.957           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.907           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.588           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.214           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.228           ms/op
ClientSimple.existUser                      sample  16371   1.953 ± 0.039   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.768           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.800           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.228           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.359           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.203           ms/op
ClientSimple.existUser:existUser·p0.999     sample         31.417           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         36.038           ms/op
ClientSimple.existUser:existUser·p1.00      sample         36.372           ms/op
ClientSimple.getUser                        sample  15932   2.007 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.633           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.872           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.436           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.662           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.478           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.266           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.553           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.592           ms/op
ClientSimple.listUser                       sample   9927   3.202 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.237           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.978           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.194           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.391           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.142           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.401           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.746           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.746           ms/op

Benchmark result is saved to 1718540114261.json
