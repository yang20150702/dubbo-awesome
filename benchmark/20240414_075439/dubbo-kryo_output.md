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
# Warmup Iteration   1: 1.616 ops/ms
Iteration   1: 6.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.765 ops/ms


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
# Warmup Iteration   1: 6.472 ops/ms
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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.253 ops/ms
Iteration   1: 11.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.392 ops/ms


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
# Warmup Iteration   1: 4.228 ops/ms
Iteration   1: 8.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.242 ops/ms


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
# Warmup Iteration   1: 4.580 ±(99.9%) 0.081 ms/op
Iteration   1: 2.190 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.190 ms/op


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
# Warmup Iteration   1: 3.231 ±(99.9%) 0.063 ms/op
Iteration   1: 2.257 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.257 ms/op


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
# Warmup Iteration   1: 3.349 ±(99.9%) 0.062 ms/op
Iteration   1: 2.079 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.671 ±(99.9%) 0.092 ms/op
Iteration   1: 3.553 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.553 ms/op


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
# Warmup Iteration   1: 3.750 ±(99.9%) 0.101 ms/op
Iteration   1: 2.177 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.582 ms/op
                 createUser·p0.50:   2.003 ms/op
                 createUser·p0.90:   2.621 ms/op
                 createUser·p0.95:   2.920 ms/op
                 createUser·p0.99:   6.431 ms/op
                 createUser·p0.999:  20.709 ms/op
                 createUser·p0.9999: 22.631 ms/op
                 createUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14690
  mean =      2.177 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12548 
    [ 2.500,  5.000) = 1842 
    [ 5.000,  7.500) = 202 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      2.003 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.920 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     20.709 ms/op
     p(99.9900) =     22.631 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 3.347 ±(99.9%) 0.087 ms/op
Iteration   1: 1.907 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.558 ms/op
                 existUser·p0.50:   1.763 ms/op
                 existUser·p0.90:   2.413 ms/op
                 existUser·p0.95:   2.605 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  13.828 ms/op
                 existUser·p0.9999: 16.886 ms/op
                 existUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16800
  mean =      1.907 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 402 
    [ 1.250,  2.500) = 15179 
    [ 2.500,  3.750) = 1039 
    [ 3.750,  5.000) = 41 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      1.763 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.605 ms/op
     p(99.0000) =      4.661 ms/op
     p(99.9000) =     13.828 ms/op
     p(99.9900) =     16.886 ms/op
     p(99.9990) =     16.908 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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
# Warmup Iteration   1: 3.525 ±(99.9%) 0.103 ms/op
Iteration   1: 2.135 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.617 ms/op
                 getUser·p0.50:   2.030 ms/op
                 getUser·p0.90:   2.654 ms/op
                 getUser·p0.95:   2.875 ms/op
                 getUser·p0.99:   5.146 ms/op
                 getUser·p0.999:  12.993 ms/op
                 getUser·p0.9999: 15.973 ms/op
                 getUser·p1.00:   16.040 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15106
  mean =      2.135 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 200 
    [ 1.250,  2.500) = 12584 
    [ 2.500,  3.750) = 2048 
    [ 3.750,  5.000) = 123 
    [ 5.000,  6.250) = 86 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      2.030 ms/op
     p(90.0000) =      2.654 ms/op
     p(95.0000) =      2.875 ms/op
     p(99.0000) =      5.146 ms/op
     p(99.9000) =     12.993 ms/op
     p(99.9900) =     15.973 ms/op
     p(99.9990) =     16.040 ms/op
     p(99.9999) =     16.040 ms/op
    p(100.0000) =     16.040 ms/op


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
# Warmup Iteration   1: 4.338 ±(99.9%) 0.125 ms/op
Iteration   1: 3.424 ±(99.9%) 0.052 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   3.117 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   6.177 ms/op
                 listUser·p0.999:  25.427 ms/op
                 listUser·p0.9999: 28.279 ms/op
                 listUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9338
  mean =      3.424 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 451 
    [ 2.500,  5.000) = 8559 
    [ 5.000,  7.500) = 257 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     25.427 ms/op
     p(99.9900) =     28.279 ms/op
     p(99.9990) =     28.279 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.765          ops/ms
ClientSimple.existUser                       thrpt         12.412          ops/ms
ClientSimple.getUser                         thrpt         11.392          ops/ms
ClientSimple.listUser                        thrpt          8.242          ops/ms
ClientSimple.createUser                       avgt          2.190           ms/op
ClientSimple.existUser                        avgt          2.257           ms/op
ClientSimple.getUser                          avgt          2.079           ms/op
ClientSimple.listUser                         avgt          3.553           ms/op
ClientSimple.createUser                     sample  14690   2.177 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.582           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.003           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.621           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.920           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.431           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.709           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.631           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.708           ms/op
ClientSimple.existUser                      sample  16800   1.907 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.558           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.763           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.413           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.605           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.661           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.828           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.886           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.908           ms/op
ClientSimple.getUser                        sample  15106   2.135 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.617           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.030           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.654           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.875           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.146           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.993           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.973           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.040           ms/op
ClientSimple.listUser                       sample   9338   3.424 ± 0.052   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.930           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.117           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.661           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.177           ms/op
ClientSimple.listUser:listUser·p0.999       sample         25.427           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         28.279           ms/op
ClientSimple.listUser:listUser·p1.00        sample         28.279           ms/op

Benchmark result is saved to 1713081026156.json
