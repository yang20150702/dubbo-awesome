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
# Warmup Iteration   1: 1.425 ops/ms
Iteration   1: 6.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.911 ops/ms


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
# Warmup Iteration   1: 5.995 ops/ms
Iteration   1: 13.293 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.293 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 7.502 ops/ms
Iteration   1: 14.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.545 ops/ms


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
# Warmup Iteration   1: 5.167 ops/ms
Iteration   1: 8.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.687 ops/ms


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
# Warmup Iteration   1: 4.042 ±(99.9%) 0.092 ms/op
Iteration   1: 2.020 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.020 ms/op


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
# Warmup Iteration   1: 2.816 ±(99.9%) 0.047 ms/op
Iteration   1: 1.853 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.853 ms/op


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
# Warmup Iteration   1: 3.199 ±(99.9%) 0.046 ms/op
Iteration   1: 2.069 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.069 ms/op


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
# Warmup Iteration   1: 4.494 ±(99.9%) 0.078 ms/op
Iteration   1: 3.670 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.670 ms/op


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
# Warmup Iteration   1: 3.245 ±(99.9%) 0.071 ms/op
Iteration   1: 1.981 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.501 ms/op
                 createUser·p0.50:   1.892 ms/op
                 createUser·p0.90:   2.474 ms/op
                 createUser·p0.95:   2.613 ms/op
                 createUser·p0.99:   6.013 ms/op
                 createUser·p0.999:  17.199 ms/op
                 createUser·p0.9999: 18.675 ms/op
                 createUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16140
  mean =      1.981 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1147 
    [ 1.250,  2.500) = 13607 
    [ 2.500,  3.750) = 1208 
    [ 3.750,  5.000) = 7 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      1.892 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.613 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     17.199 ms/op
     p(99.9900) =     18.675 ms/op
     p(99.9990) =     18.776 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 2.857 ±(99.9%) 0.070 ms/op
Iteration   1: 1.773 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   1.694 ms/op
                 existUser·p0.90:   2.167 ms/op
                 existUser·p0.95:   2.298 ms/op
                 existUser·p0.99:   3.177 ms/op
                 existUser·p0.999:  15.958 ms/op
                 existUser·p0.9999: 16.353 ms/op
                 existUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18045
  mean =      1.773 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1156 
    [ 1.250,  2.500) = 16412 
    [ 2.500,  3.750) = 314 
    [ 3.750,  5.000) = 89 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      1.694 ms/op
     p(90.0000) =      2.167 ms/op
     p(95.0000) =      2.298 ms/op
     p(99.0000) =      3.177 ms/op
     p(99.9000) =     15.958 ms/op
     p(99.9900) =     16.353 ms/op
     p(99.9990) =     16.695 ms/op
     p(99.9999) =     16.695 ms/op
    p(100.0000) =     16.695 ms/op


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
# Warmup Iteration   1: 3.178 ±(99.9%) 0.074 ms/op
Iteration   1: 1.843 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   1.722 ms/op
                 getUser·p0.90:   2.236 ms/op
                 getUser·p0.95:   2.392 ms/op
                 getUser·p0.99:   3.191 ms/op
                 getUser·p0.999:  15.761 ms/op
                 getUser·p0.9999: 16.016 ms/op
                 getUser·p1.00:   16.040 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17341
  mean =      1.843 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 224 
    [ 1.250,  2.500) = 16488 
    [ 2.500,  3.750) = 480 
    [ 3.750,  5.000) = 55 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      1.722 ms/op
     p(90.0000) =      2.236 ms/op
     p(95.0000) =      2.392 ms/op
     p(99.0000) =      3.191 ms/op
     p(99.9000) =     15.761 ms/op
     p(99.9900) =     16.016 ms/op
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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.139 ±(99.9%) 0.098 ms/op
Iteration   1: 3.190 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.427 ms/op
                 listUser·p0.50:   3.101 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.194 ms/op
                 listUser·p0.999:  6.406 ms/op
                 listUser·p0.9999: 11.419 ms/op
                 listUser·p1.00:   11.436 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10039
  mean =      3.190 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1729 
    [ 2.500,  3.750) = 6197 
    [ 3.750,  5.000) = 1973 
    [ 5.000,  6.250) = 130 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.427 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.194 ms/op
     p(99.9000) =      6.406 ms/op
     p(99.9900) =     11.419 ms/op
     p(99.9990) =     11.436 ms/op
     p(99.9999) =     11.436 ms/op
    p(100.0000) =     11.436 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.911          ops/ms
ClientSimple.existUser                       thrpt         13.293          ops/ms
ClientSimple.getUser                         thrpt         14.545          ops/ms
ClientSimple.listUser                        thrpt          8.687          ops/ms
ClientSimple.createUser                       avgt          2.020           ms/op
ClientSimple.existUser                        avgt          1.853           ms/op
ClientSimple.getUser                          avgt          2.069           ms/op
ClientSimple.listUser                         avgt          3.670           ms/op
ClientSimple.createUser                     sample  16140   1.981 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.501           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.892           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.474           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.613           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.013           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.199           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.675           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.776           ms/op
ClientSimple.existUser                      sample  18045   1.773 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.791           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.694           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.167           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.298           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.177           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.958           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.353           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.695           ms/op
ClientSimple.getUser                        sample  17341   1.843 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.815           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.722           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.236           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.392           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.191           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.761           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.016           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.040           ms/op
ClientSimple.listUser                       sample  10039   3.190 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.427           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.101           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.088           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.391           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.194           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.406           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.419           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.436           ms/op

Benchmark result is saved to 1713550230499.json
