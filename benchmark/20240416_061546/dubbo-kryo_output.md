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
# Warmup Iteration   1: 1.904 ops/ms
Iteration   1: 8.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.236 ops/ms


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
# Warmup Iteration   1: 5.369 ops/ms
Iteration   1: 11.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.288 ops/ms


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
# Warmup Iteration   1: 5.871 ops/ms
Iteration   1: 11.770 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.770 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.547 ops/ms
Iteration   1: 9.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.641 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.956 ±(99.9%) 0.066 ms/op
Iteration   1: 2.226 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.226 ms/op


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
# Warmup Iteration   1: 3.156 ±(99.9%) 0.047 ms/op
Iteration   1: 1.924 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.924 ms/op


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
# Warmup Iteration   1: 3.253 ±(99.9%) 0.048 ms/op
Iteration   1: 2.279 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.279 ms/op


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
# Warmup Iteration   1: 4.376 ±(99.9%) 0.098 ms/op
Iteration   1: 3.360 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.360 ms/op


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
# Warmup Iteration   1: 3.706 ±(99.9%) 0.111 ms/op
Iteration   1: 2.645 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.496 ms/op
                 createUser·p0.50:   2.413 ms/op
                 createUser·p0.90:   3.191 ms/op
                 createUser·p0.95:   3.738 ms/op
                 createUser·p0.99:   9.198 ms/op
                 createUser·p0.999:  13.992 ms/op
                 createUser·p0.9999: 17.955 ms/op
                 createUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12086
  mean =      2.645 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 6797 
    [ 2.500,  3.750) = 4619 
    [ 3.750,  5.000) = 239 
    [ 5.000,  6.250) = 93 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 81 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.496 ms/op
     p(50.0000) =      2.413 ms/op
     p(90.0000) =      3.191 ms/op
     p(95.0000) =      3.738 ms/op
     p(99.0000) =      9.198 ms/op
     p(99.9000) =     13.992 ms/op
     p(99.9900) =     17.955 ms/op
     p(99.9990) =     17.990 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.047 ±(99.9%) 0.066 ms/op
Iteration   1: 1.838 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.630 ms/op
                 existUser·p0.50:   1.763 ms/op
                 existUser·p0.90:   2.241 ms/op
                 existUser·p0.95:   2.429 ms/op
                 existUser·p0.99:   2.814 ms/op
                 existUser·p0.999:  11.223 ms/op
                 existUser·p0.9999: 11.420 ms/op
                 existUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17487
  mean =      1.838 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 393 
    [ 1.250,  2.500) = 16453 
    [ 2.500,  3.750) = 565 
    [ 3.750,  5.000) = 39 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      1.763 ms/op
     p(90.0000) =      2.241 ms/op
     p(95.0000) =      2.429 ms/op
     p(99.0000) =      2.814 ms/op
     p(99.9000) =     11.223 ms/op
     p(99.9900) =     11.420 ms/op
     p(99.9990) =     11.420 ms/op
     p(99.9999) =     11.420 ms/op
    p(100.0000) =     11.420 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.533 ±(99.9%) 0.091 ms/op
Iteration   1: 1.892 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.428 ms/op
                 getUser·p0.50:   1.802 ms/op
                 getUser·p0.90:   2.212 ms/op
                 getUser·p0.95:   2.481 ms/op
                 getUser·p0.99:   3.175 ms/op
                 getUser·p0.999:  16.269 ms/op
                 getUser·p0.9999: 16.918 ms/op
                 getUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16883
  mean =      1.892 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 171 
    [ 1.250,  2.500) = 15917 
    [ 2.500,  3.750) = 708 
    [ 3.750,  5.000) = 12 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.428 ms/op
     p(50.0000) =      1.802 ms/op
     p(90.0000) =      2.212 ms/op
     p(95.0000) =      2.481 ms/op
     p(99.0000) =      3.175 ms/op
     p(99.9000) =     16.269 ms/op
     p(99.9900) =     16.918 ms/op
     p(99.9990) =     16.941 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


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
# Warmup Iteration   1: 4.153 ±(99.9%) 0.122 ms/op
Iteration   1: 3.326 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   1.006 ms/op
                 listUser·p0.50:   3.047 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   8.004 ms/op
                 listUser·p0.999:  19.490 ms/op
                 listUser·p0.9999: 20.283 ms/op
                 listUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9599
  mean =      3.326 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1476 
    [ 2.500,  5.000) = 7649 
    [ 5.000,  7.500) = 378 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      8.004 ms/op
     p(99.9000) =     19.490 ms/op
     p(99.9900) =     20.283 ms/op
     p(99.9990) =     20.283 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.236          ops/ms
ClientSimple.existUser                       thrpt         11.288          ops/ms
ClientSimple.getUser                         thrpt         11.770          ops/ms
ClientSimple.listUser                        thrpt          9.641          ops/ms
ClientSimple.createUser                       avgt          2.226           ms/op
ClientSimple.existUser                        avgt          1.924           ms/op
ClientSimple.getUser                          avgt          2.279           ms/op
ClientSimple.listUser                         avgt          3.360           ms/op
ClientSimple.createUser                     sample  12086   2.645 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.496           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.413           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.191           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.738           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.198           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.992           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.955           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.990           ms/op
ClientSimple.existUser                      sample  17487   1.838 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.630           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.763           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.241           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.429           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.814           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.223           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.420           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.420           ms/op
ClientSimple.getUser                        sample  16883   1.892 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.428           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.802           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.212           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.481           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.175           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.269           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.918           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.941           ms/op
ClientSimple.listUser                       sample   9599   3.326 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.006           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.047           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.989           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.004           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.490           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.283           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.283           ms/op

Benchmark result is saved to 1713247879406.json
