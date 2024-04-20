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
# Warmup Iteration   1: 1.911 ops/ms
Iteration   1: 7.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.416 ops/ms


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
# Warmup Iteration   1: 6.848 ops/ms
Iteration   1: 13.612 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.612 ops/ms


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
# Warmup Iteration   1: 6.158 ops/ms
Iteration   1: 12.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.498 ops/ms


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
# Warmup Iteration   1: 4.958 ops/ms
Iteration   1: 8.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.752 ops/ms


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
# Warmup Iteration   1: 4.015 ±(99.9%) 0.076 ms/op
Iteration   1: 2.079 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.079 ms/op


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
# Warmup Iteration   1: 3.046 ±(99.9%) 0.047 ms/op
Iteration   1: 1.882 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.882 ms/op


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
# Warmup Iteration   1: 3.162 ±(99.9%) 0.061 ms/op
Iteration   1: 2.235 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.235 ms/op


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
# Warmup Iteration   1: 4.379 ±(99.9%) 0.090 ms/op
Iteration   1: 3.322 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.322 ms/op


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
# Warmup Iteration   1: 3.468 ±(99.9%) 0.089 ms/op
Iteration   1: 2.373 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.465 ms/op
                 createUser·p0.50:   2.220 ms/op
                 createUser·p0.90:   2.712 ms/op
                 createUser·p0.95:   2.953 ms/op
                 createUser·p0.99:   8.536 ms/op
                 createUser·p0.999:  24.642 ms/op
                 createUser·p0.9999: 25.596 ms/op
                 createUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13478
  mean =      2.373 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10631 
    [ 2.500,  5.000) = 2569 
    [ 5.000,  7.500) = 133 
    [ 7.500, 10.000) = 110 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.465 ms/op
     p(50.0000) =      2.220 ms/op
     p(90.0000) =      2.712 ms/op
     p(95.0000) =      2.953 ms/op
     p(99.0000) =      8.536 ms/op
     p(99.9000) =     24.642 ms/op
     p(99.9900) =     25.596 ms/op
     p(99.9990) =     26.018 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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
# Warmup Iteration   1: 3.365 ±(99.9%) 0.083 ms/op
Iteration   1: 2.064 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.442 ms/op
                 existUser·p0.50:   1.788 ms/op
                 existUser·p0.90:   2.879 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   4.007 ms/op
                 existUser·p0.999:  20.840 ms/op
                 existUser·p0.9999: 22.397 ms/op
                 existUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15495
  mean =      2.064 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12691 
    [ 2.500,  5.000) = 2732 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.442 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.879 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      4.007 ms/op
     p(99.9000) =     20.840 ms/op
     p(99.9900) =     22.397 ms/op
     p(99.9990) =     22.577 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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
# Warmup Iteration   1: 3.288 ±(99.9%) 0.081 ms/op
Iteration   1: 2.190 ±(99.9%) 0.056 ms/op
                 getUser·p0.00:   0.606 ms/op
                 getUser·p0.50:   1.960 ms/op
                 getUser·p0.90:   2.548 ms/op
                 getUser·p0.95:   2.736 ms/op
                 getUser·p0.99:   4.947 ms/op
                 getUser·p0.999:  45.109 ms/op
                 getUser·p0.9999: 46.998 ms/op
                 getUser·p1.00:   47.120 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14685
  mean =      2.190 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14542 
    [ 5.000, 10.000) = 40 
    [10.000, 15.000) = 67 
    [15.000, 20.000) = 1 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      1.960 ms/op
     p(90.0000) =      2.548 ms/op
     p(95.0000) =      2.736 ms/op
     p(99.0000) =      4.947 ms/op
     p(99.9000) =     45.109 ms/op
     p(99.9900) =     46.998 ms/op
     p(99.9990) =     47.120 ms/op
     p(99.9999) =     47.120 ms/op
    p(100.0000) =     47.120 ms/op


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
# Warmup Iteration   1: 4.316 ±(99.9%) 0.124 ms/op
Iteration   1: 3.268 ±(99.9%) 0.058 ms/op
                 listUser·p0.00:   1.023 ms/op
                 listUser·p0.50:   3.056 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.365 ms/op
                 listUser·p0.999:  30.743 ms/op
                 listUser·p0.9999: 31.064 ms/op
                 listUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9806
  mean =      3.268 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1369 
    [ 2.500,  5.000) = 8250 
    [ 5.000,  7.500) = 123 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.023 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     30.743 ms/op
     p(99.9900) =     31.064 ms/op
     p(99.9990) =     31.064 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.416          ops/ms
ClientSimple.existUser                       thrpt         13.612          ops/ms
ClientSimple.getUser                         thrpt         12.498          ops/ms
ClientSimple.listUser                        thrpt          8.752          ops/ms
ClientSimple.createUser                       avgt          2.079           ms/op
ClientSimple.existUser                        avgt          1.882           ms/op
ClientSimple.getUser                          avgt          2.235           ms/op
ClientSimple.listUser                         avgt          3.322           ms/op
ClientSimple.createUser                     sample  13478   2.373 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.465           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.220           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.712           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.953           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.536           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.642           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.596           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.018           ms/op
ClientSimple.existUser                      sample  15495   2.064 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.442           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.788           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.879           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.133           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.007           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.840           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.397           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.577           ms/op
ClientSimple.getUser                        sample  14685   2.190 ± 0.056   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.606           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.960           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.548           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.736           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.947           ms/op
ClientSimple.getUser:getUser·p0.999         sample         45.109           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         46.998           ms/op
ClientSimple.getUser:getUser·p1.00          sample         47.120           ms/op
ClientSimple.listUser                       sample   9806   3.268 ± 0.058   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.023           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.056           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.977           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.365           ms/op
ClientSimple.listUser:listUser·p0.999       sample         30.743           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         31.064           ms/op
ClientSimple.listUser:listUser·p1.00        sample         31.064           ms/op

Benchmark result is saved to 1713615237308.json
