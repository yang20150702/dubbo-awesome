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
# Warmup Iteration   1: 1.808 ops/ms
Iteration   1: 5.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.623 ops/ms


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
# Warmup Iteration   1: 5.793 ops/ms
Iteration   1: 11.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.867 ops/ms


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
# Warmup Iteration   1: 5.019 ops/ms
Iteration   1: 10.235 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.235 ops/ms


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
# Warmup Iteration   1: 4.812 ops/ms
Iteration   1: 7.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.983 ops/ms


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
# Warmup Iteration   1: 4.233 ±(99.9%) 0.088 ms/op
Iteration   1: 2.424 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.424 ms/op


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
# Warmup Iteration   1: 3.202 ±(99.9%) 0.051 ms/op
Iteration   1: 2.156 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.156 ms/op


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
# Warmup Iteration   1: 3.262 ±(99.9%) 0.058 ms/op
Iteration   1: 2.137 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.137 ms/op


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
# Warmup Iteration   1: 4.291 ±(99.9%) 0.093 ms/op
Iteration   1: 3.303 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.303 ms/op


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
# Warmup Iteration   1: 3.461 ±(99.9%) 0.102 ms/op
Iteration   1: 2.033 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.541 ms/op
                 createUser·p0.50:   1.930 ms/op
                 createUser·p0.90:   2.519 ms/op
                 createUser·p0.95:   2.736 ms/op
                 createUser·p0.99:   6.027 ms/op
                 createUser·p0.999:  15.876 ms/op
                 createUser·p0.9999: 22.259 ms/op
                 createUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15714
  mean =      2.033 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14066 
    [ 2.500,  5.000) = 1435 
    [ 5.000,  7.500) = 65 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      1.930 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.736 ms/op
     p(99.0000) =      6.027 ms/op
     p(99.9000) =     15.876 ms/op
     p(99.9900) =     22.259 ms/op
     p(99.9990) =     22.315 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


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
# Warmup Iteration   1: 3.083 ±(99.9%) 0.067 ms/op
Iteration   1: 1.799 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.357 ms/op
                 existUser·p0.50:   1.696 ms/op
                 existUser·p0.90:   2.122 ms/op
                 existUser·p0.95:   2.318 ms/op
                 existUser·p0.99:   2.967 ms/op
                 existUser·p0.999:  24.557 ms/op
                 existUser·p0.9999: 25.024 ms/op
                 existUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17790
  mean =      1.799 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17352 
    [ 2.500,  5.000) = 357 
    [ 5.000,  7.500) = 17 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.357 ms/op
     p(50.0000) =      1.696 ms/op
     p(90.0000) =      2.122 ms/op
     p(95.0000) =      2.318 ms/op
     p(99.0000) =      2.967 ms/op
     p(99.9000) =     24.557 ms/op
     p(99.9900) =     25.024 ms/op
     p(99.9990) =     25.100 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


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
# Warmup Iteration   1: 3.437 ±(99.9%) 0.099 ms/op
Iteration   1: 2.104 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.515 ms/op
                 getUser·p0.50:   1.997 ms/op
                 getUser·p0.90:   2.658 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.178 ms/op
                 getUser·p0.999:  11.822 ms/op
                 getUser·p0.9999: 12.172 ms/op
                 getUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15459
  mean =      2.104 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 13206 
    [ 2.500,  3.750) = 1934 
    [ 3.750,  5.000) = 136 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      1.997 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      4.178 ms/op
     p(99.9000) =     11.822 ms/op
     p(99.9900) =     12.172 ms/op
     p(99.9990) =     12.190 ms/op
     p(99.9999) =     12.190 ms/op
    p(100.0000) =     12.190 ms/op


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
# Warmup Iteration   1: 4.454 ±(99.9%) 0.121 ms/op
Iteration   1: 3.458 ±(99.9%) 0.074 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.396 ms/op
                 listUser·p0.90:   4.217 ms/op
                 listUser·p0.95:   4.533 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  37.209 ms/op
                 listUser·p0.9999: 37.814 ms/op
                 listUser·p1.00:   37.814 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9231
  mean =      3.458 ±(99.9%) 0.074 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1179 
    [ 2.500,  5.000) = 7810 
    [ 5.000,  7.500) = 145 
    [ 7.500, 10.000) = 65 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.217 ms/op
     p(95.0000) =      4.533 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     37.209 ms/op
     p(99.9900) =     37.814 ms/op
     p(99.9990) =     37.814 ms/op
     p(99.9999) =     37.814 ms/op
    p(100.0000) =     37.814 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.623          ops/ms
ClientSimple.existUser                       thrpt         11.867          ops/ms
ClientSimple.getUser                         thrpt         10.235          ops/ms
ClientSimple.listUser                        thrpt          7.983          ops/ms
ClientSimple.createUser                       avgt          2.424           ms/op
ClientSimple.existUser                        avgt          2.156           ms/op
ClientSimple.getUser                          avgt          2.137           ms/op
ClientSimple.listUser                         avgt          3.303           ms/op
ClientSimple.createUser                     sample  15714   2.033 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.541           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.930           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.519           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.736           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.027           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.876           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.259           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.315           ms/op
ClientSimple.existUser                      sample  17790   1.799 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.357           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.696           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.122           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.318           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.967           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.557           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.024           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.100           ms/op
ClientSimple.getUser                        sample  15459   2.104 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.515           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.997           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.658           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.236           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.178           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.822           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.172           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.190           ms/op
ClientSimple.listUser                       sample   9231   3.458 ± 0.074   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.143           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.396           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.217           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.533           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.561           ms/op
ClientSimple.listUser:listUser·p0.999       sample         37.209           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         37.814           ms/op
ClientSimple.listUser:listUser·p1.00        sample         37.814           ms/op

Benchmark result is saved to 1715494319205.json
