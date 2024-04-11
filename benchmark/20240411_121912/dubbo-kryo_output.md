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
# Warmup Iteration   1: 1.020 ops/ms
Iteration   1: 6.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.950 ops/ms


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
# Warmup Iteration   1: 6.259 ops/ms
Iteration   1: 12.685 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.685 ops/ms


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
# Warmup Iteration   1: 6.475 ops/ms
Iteration   1: 12.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.534 ops/ms


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
# Warmup Iteration   1: 3.850 ops/ms
Iteration   1: 7.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.407 ops/ms


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
# Warmup Iteration   1: 3.962 ±(99.9%) 0.091 ms/op
Iteration   1: 2.246 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.246 ms/op


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
# Warmup Iteration   1: 3.041 ±(99.9%) 0.051 ms/op
Iteration   1: 1.814 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.814 ms/op


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
# Warmup Iteration   1: 3.332 ±(99.9%) 0.061 ms/op
Iteration   1: 1.918 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.918 ms/op


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
# Warmup Iteration   1: 4.151 ±(99.9%) 0.100 ms/op
Iteration   1: 3.468 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.468 ms/op


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
# Warmup Iteration   1: 3.571 ±(99.9%) 0.121 ms/op
Iteration   1: 2.345 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.513 ms/op
                 createUser·p0.50:   2.146 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.469 ms/op
                 createUser·p0.99:   7.379 ms/op
                 createUser·p0.999:  16.810 ms/op
                 createUser·p0.9999: 17.699 ms/op
                 createUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13726
  mean =      2.345 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 526 
    [ 1.250,  2.500) = 9155 
    [ 2.500,  3.750) = 3582 
    [ 3.750,  5.000) = 104 
    [ 5.000,  6.250) = 143 
    [ 6.250,  7.500) = 92 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      2.146 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.469 ms/op
     p(99.0000) =      7.379 ms/op
     p(99.9000) =     16.810 ms/op
     p(99.9900) =     17.699 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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
# Warmup Iteration   1: 2.937 ±(99.9%) 0.063 ms/op
Iteration   1: 1.883 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.514 ms/op
                 existUser·p0.50:   1.860 ms/op
                 existUser·p0.90:   2.281 ms/op
                 existUser·p0.95:   2.404 ms/op
                 existUser·p0.99:   2.970 ms/op
                 existUser·p0.999:  27.525 ms/op
                 existUser·p0.9999: 27.754 ms/op
                 existUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16999
  mean =      1.883 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16388 
    [ 2.500,  5.000) = 578 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.514 ms/op
     p(50.0000) =      1.860 ms/op
     p(90.0000) =      2.281 ms/op
     p(95.0000) =      2.404 ms/op
     p(99.0000) =      2.970 ms/op
     p(99.9000) =     27.525 ms/op
     p(99.9900) =     27.754 ms/op
     p(99.9990) =     27.754 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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
# Warmup Iteration   1: 3.225 ±(99.9%) 0.080 ms/op
Iteration   1: 2.146 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.606 ms/op
                 getUser·p0.50:   2.042 ms/op
                 getUser·p0.90:   2.585 ms/op
                 getUser·p0.95:   2.769 ms/op
                 getUser·p0.99:   5.079 ms/op
                 getUser·p0.999:  12.993 ms/op
                 getUser·p0.9999: 22.382 ms/op
                 getUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14904
  mean =      2.146 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12861 
    [ 2.500,  5.000) = 1884 
    [ 5.000,  7.500) = 96 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      2.042 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.769 ms/op
     p(99.0000) =      5.079 ms/op
     p(99.9000) =     12.993 ms/op
     p(99.9900) =     22.382 ms/op
     p(99.9990) =     22.446 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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
# Warmup Iteration   1: 4.456 ±(99.9%) 0.131 ms/op
Iteration   1: 3.678 ±(99.9%) 0.053 ms/op
                 listUser·p0.00:   0.770 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   5.940 ms/op
                 listUser·p0.999:  24.379 ms/op
                 listUser·p0.9999: 24.740 ms/op
                 listUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8692
  mean =      3.678 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 582 
    [ 2.500,  5.000) = 7706 
    [ 5.000,  7.500) = 333 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      5.940 ms/op
     p(99.9000) =     24.379 ms/op
     p(99.9900) =     24.740 ms/op
     p(99.9990) =     24.740 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.950          ops/ms
ClientSimple.existUser                       thrpt         12.685          ops/ms
ClientSimple.getUser                         thrpt         12.534          ops/ms
ClientSimple.listUser                        thrpt          7.407          ops/ms
ClientSimple.createUser                       avgt          2.246           ms/op
ClientSimple.existUser                        avgt          1.814           ms/op
ClientSimple.getUser                          avgt          1.918           ms/op
ClientSimple.listUser                         avgt          3.468           ms/op
ClientSimple.createUser                     sample  13726   2.345 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.513           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.146           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.031           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.469           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.379           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.810           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.699           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.760           ms/op
ClientSimple.existUser                      sample  16999   1.883 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.514           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.860           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.281           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.404           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.970           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.525           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.754           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.754           ms/op
ClientSimple.getUser                        sample  14904   2.146 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.606           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.042           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.585           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.769           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.079           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.993           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.382           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.446           ms/op
ClientSimple.listUser                       sample   8692   3.678 ± 0.053   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.770           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.690           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.489           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.923           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.940           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.379           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.740           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.740           ms/op

Benchmark result is saved to 1712837701686.json
