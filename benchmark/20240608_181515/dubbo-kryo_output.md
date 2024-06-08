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
# Warmup Iteration   1: 2.032 ops/ms
Iteration   1: 7.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.243 ops/ms


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
# Warmup Iteration   1: 5.929 ops/ms
Iteration   1: 11.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.608 ops/ms


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
# Warmup Iteration   1: 5.749 ops/ms
Iteration   1: 11.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.660 ops/ms


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
# Warmup Iteration   1: 3.915 ops/ms
Iteration   1: 8.342 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.342 ops/ms


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
# Warmup Iteration   1: 3.828 ±(99.9%) 0.074 ms/op
Iteration   1: 2.158 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.158 ms/op


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
# Warmup Iteration   1: 3.355 ±(99.9%) 0.069 ms/op
Iteration   1: 1.870 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.870 ms/op


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
# Warmup Iteration   1: 3.715 ±(99.9%) 0.075 ms/op
Iteration   1: 2.244 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.244 ms/op


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
# Warmup Iteration   1: 4.408 ±(99.9%) 0.080 ms/op
Iteration   1: 3.442 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.442 ms/op


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
# Warmup Iteration   1: 3.442 ±(99.9%) 0.088 ms/op
Iteration   1: 2.118 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.450 ms/op
                 createUser·p0.50:   1.804 ms/op
                 createUser·p0.90:   2.757 ms/op
                 createUser·p0.95:   2.978 ms/op
                 createUser·p0.99:   6.136 ms/op
                 createUser·p0.999:  26.739 ms/op
                 createUser·p0.9999: 27.266 ms/op
                 createUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15196
  mean =      2.118 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12516 
    [ 2.500,  5.000) = 2477 
    [ 5.000,  7.500) = 75 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      1.804 ms/op
     p(90.0000) =      2.757 ms/op
     p(95.0000) =      2.978 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     26.739 ms/op
     p(99.9900) =     27.266 ms/op
     p(99.9990) =     27.623 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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
# Warmup Iteration   1: 3.066 ±(99.9%) 0.079 ms/op
Iteration   1: 1.753 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.744 ms/op
                 existUser·p0.50:   1.597 ms/op
                 existUser·p0.90:   2.421 ms/op
                 existUser·p0.95:   2.662 ms/op
                 existUser·p0.99:   4.126 ms/op
                 existUser·p0.999:  9.814 ms/op
                 existUser·p0.9999: 11.107 ms/op
                 existUser·p1.00:   11.256 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18238
  mean =      1.753 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2530 
    [ 1.250,  2.500) = 14299 
    [ 2.500,  3.750) = 1187 
    [ 3.750,  5.000) = 93 
    [ 5.000,  6.250) = 95 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      1.597 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =      4.126 ms/op
     p(99.9000) =      9.814 ms/op
     p(99.9900) =     11.107 ms/op
     p(99.9990) =     11.256 ms/op
     p(99.9999) =     11.256 ms/op
    p(100.0000) =     11.256 ms/op


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
# Warmup Iteration   1: 3.313 ±(99.9%) 0.076 ms/op
Iteration   1: 1.841 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.675 ms/op
                 getUser·p0.50:   1.759 ms/op
                 getUser·p0.90:   2.083 ms/op
                 getUser·p0.95:   2.359 ms/op
                 getUser·p0.99:   3.463 ms/op
                 getUser·p0.999:  11.609 ms/op
                 getUser·p0.9999: 11.964 ms/op
                 getUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17458
  mean =      1.841 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 16767 
    [ 2.500,  3.750) = 522 
    [ 3.750,  5.000) = 34 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      1.759 ms/op
     p(90.0000) =      2.083 ms/op
     p(95.0000) =      2.359 ms/op
     p(99.0000) =      3.463 ms/op
     p(99.9000) =     11.609 ms/op
     p(99.9900) =     11.964 ms/op
     p(99.9990) =     11.977 ms/op
     p(99.9999) =     11.977 ms/op
    p(100.0000) =     11.977 ms/op


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
# Warmup Iteration   1: 4.693 ±(99.9%) 0.134 ms/op
Iteration   1: 3.124 ±(99.9%) 0.060 ms/op
                 listUser·p0.00:   1.235 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   5.313 ms/op
                 listUser·p0.999:  32.309 ms/op
                 listUser·p0.9999: 32.375 ms/op
                 listUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10221
  mean =      3.124 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1481 
    [ 2.500,  5.000) = 8628 
    [ 5.000,  7.500) = 43 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.313 ms/op
     p(99.9000) =     32.309 ms/op
     p(99.9900) =     32.375 ms/op
     p(99.9990) =     32.375 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.243          ops/ms
ClientSimple.existUser                       thrpt         11.608          ops/ms
ClientSimple.getUser                         thrpt         11.660          ops/ms
ClientSimple.listUser                        thrpt          8.342          ops/ms
ClientSimple.createUser                       avgt          2.158           ms/op
ClientSimple.existUser                        avgt          1.870           ms/op
ClientSimple.getUser                          avgt          2.244           ms/op
ClientSimple.listUser                         avgt          3.442           ms/op
ClientSimple.createUser                     sample  15196   2.118 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.450           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.804           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.757           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.978           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.136           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.739           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.266           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.623           ms/op
ClientSimple.existUser                      sample  18238   1.753 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.744           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.597           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.421           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.662           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.126           ms/op
ClientSimple.existUser:existUser·p0.999     sample          9.814           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.107           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.256           ms/op
ClientSimple.getUser                        sample  17458   1.841 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.675           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.759           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.083           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.359           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.463           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.609           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.964           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.977           ms/op
ClientSimple.listUser                       sample  10221   3.124 ± 0.060   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.235           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.879           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.920           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.313           ms/op
ClientSimple.listUser:listUser·p0.999       sample         32.309           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         32.375           ms/op
ClientSimple.listUser:listUser·p1.00        sample         32.375           ms/op

Benchmark result is saved to 1717870263029.json
