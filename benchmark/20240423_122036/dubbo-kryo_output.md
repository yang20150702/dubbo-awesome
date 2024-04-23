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
# Warmup Iteration   1: 1.739 ops/ms
Iteration   1: 7.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.226 ops/ms


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
# Warmup Iteration   1: 6.226 ops/ms
Iteration   1: 12.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.411 ops/ms


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
# Warmup Iteration   1: 5.835 ops/ms
Iteration   1: 13.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.164 ops/ms


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
# Warmup Iteration   1: 4.957 ops/ms
Iteration   1: 8.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.845 ops/ms


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
# Warmup Iteration   1: 4.110 ±(99.9%) 0.088 ms/op
Iteration   1: 2.300 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.300 ms/op


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
# Warmup Iteration   1: 3.424 ±(99.9%) 0.054 ms/op
Iteration   1: 1.791 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.791 ms/op


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
# Warmup Iteration   1: 3.270 ±(99.9%) 0.050 ms/op
Iteration   1: 1.949 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.949 ms/op


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
# Warmup Iteration   1: 5.565 ±(99.9%) 0.107 ms/op
Iteration   1: 3.591 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.591 ms/op


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
# Warmup Iteration   1: 3.852 ±(99.9%) 0.099 ms/op
Iteration   1: 2.232 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   2.091 ms/op
                 createUser·p0.90:   2.744 ms/op
                 createUser·p0.95:   2.966 ms/op
                 createUser·p0.99:   5.071 ms/op
                 createUser·p0.999:  14.248 ms/op
                 createUser·p0.9999: 14.956 ms/op
                 createUser·p1.00:   15.434 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14352
  mean =      2.232 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 11232 
    [ 2.500,  3.750) = 2785 
    [ 3.750,  5.000) = 136 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      2.091 ms/op
     p(90.0000) =      2.744 ms/op
     p(95.0000) =      2.966 ms/op
     p(99.0000) =      5.071 ms/op
     p(99.9000) =     14.248 ms/op
     p(99.9900) =     14.956 ms/op
     p(99.9990) =     15.434 ms/op
     p(99.9999) =     15.434 ms/op
    p(100.0000) =     15.434 ms/op


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
# Warmup Iteration   1: 3.129 ±(99.9%) 0.074 ms/op
Iteration   1: 1.877 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.450 ms/op
                 existUser·p0.50:   1.815 ms/op
                 existUser·p0.90:   2.445 ms/op
                 existUser·p0.95:   2.605 ms/op
                 existUser·p0.99:   3.377 ms/op
                 existUser·p0.999:  11.960 ms/op
                 existUser·p0.9999: 12.506 ms/op
                 existUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17028
  mean =      1.877 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 709 
    [ 1.250,  2.500) = 14993 
    [ 2.500,  3.750) = 1190 
    [ 3.750,  5.000) = 90 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      1.815 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.605 ms/op
     p(99.0000) =      3.377 ms/op
     p(99.9000) =     11.960 ms/op
     p(99.9900) =     12.506 ms/op
     p(99.9990) =     12.517 ms/op
     p(99.9999) =     12.517 ms/op
    p(100.0000) =     12.517 ms/op


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
# Warmup Iteration   1: 3.416 ±(99.9%) 0.112 ms/op
Iteration   1: 1.975 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.668 ms/op
                 getUser·p0.50:   1.866 ms/op
                 getUser·p0.90:   2.445 ms/op
                 getUser·p0.95:   2.658 ms/op
                 getUser·p0.99:   3.662 ms/op
                 getUser·p0.999:  11.563 ms/op
                 getUser·p0.9999: 11.633 ms/op
                 getUser·p1.00:   11.633 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16275
  mean =      1.975 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 14858 
    [ 2.500,  3.750) = 1182 
    [ 3.750,  5.000) = 83 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      1.866 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.658 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =     11.563 ms/op
     p(99.9900) =     11.633 ms/op
     p(99.9990) =     11.633 ms/op
     p(99.9999) =     11.633 ms/op
    p(100.0000) =     11.633 ms/op


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
# Warmup Iteration   1: 4.402 ±(99.9%) 0.135 ms/op
Iteration   1: 3.382 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.839 ms/op
                 listUser·p0.50:   3.097 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  12.297 ms/op
                 listUser·p0.9999: 13.058 ms/op
                 listUser·p1.00:   13.058 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9453
  mean =      3.382 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 634 
    [ 2.500,  3.750) = 6162 
    [ 3.750,  5.000) = 2340 
    [ 5.000,  6.250) = 154 
    [ 6.250,  7.500) = 105 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     12.297 ms/op
     p(99.9900) =     13.058 ms/op
     p(99.9990) =     13.058 ms/op
     p(99.9999) =     13.058 ms/op
    p(100.0000) =     13.058 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.226          ops/ms
ClientSimple.existUser                       thrpt         12.411          ops/ms
ClientSimple.getUser                         thrpt         13.164          ops/ms
ClientSimple.listUser                        thrpt          8.845          ops/ms
ClientSimple.createUser                       avgt          2.300           ms/op
ClientSimple.existUser                        avgt          1.791           ms/op
ClientSimple.getUser                          avgt          1.949           ms/op
ClientSimple.listUser                         avgt          3.591           ms/op
ClientSimple.createUser                     sample  14352   2.232 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.876           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.091           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.744           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.966           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.071           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.248           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.956           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.434           ms/op
ClientSimple.existUser                      sample  17028   1.877 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.450           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.815           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.445           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.605           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.377           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.960           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.506           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.517           ms/op
ClientSimple.getUser                        sample  16275   1.975 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.668           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.866           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.445           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.658           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.662           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.563           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.633           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.633           ms/op
ClientSimple.listUser                       sample   9453   3.382 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.839           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.097           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.579           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.734           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.297           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.058           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.058           ms/op

Benchmark result is saved to 1713874569892.json
