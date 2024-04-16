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
# Warmup Iteration   1: 1.717 ops/ms
Iteration   1: 6.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.252 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.191 ops/ms
Iteration   1: 12.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.577 ops/ms


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
# Warmup Iteration   1: 6.653 ops/ms
Iteration   1: 13.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.620 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.372 ops/ms
Iteration   1: 8.770 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.770 ops/ms


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
# Warmup Iteration   1: 4.126 ±(99.9%) 0.072 ms/op
Iteration   1: 2.346 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.346 ms/op


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
# Warmup Iteration   1: 3.410 ±(99.9%) 0.053 ms/op
Iteration   1: 1.861 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.861 ms/op


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
# Warmup Iteration   1: 3.425 ±(99.9%) 0.096 ms/op
Iteration   1: 1.972 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.972 ms/op


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
# Warmup Iteration   1: 4.251 ±(99.9%) 0.096 ms/op
Iteration   1: 3.353 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.353 ms/op


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
# Warmup Iteration   1: 3.578 ±(99.9%) 0.100 ms/op
Iteration   1: 2.243 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   1.999 ms/op
                 createUser·p0.90:   2.683 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   6.955 ms/op
                 createUser·p0.999:  32.014 ms/op
                 createUser·p0.9999: 34.323 ms/op
                 createUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14259
  mean =      2.243 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11893 
    [ 2.500,  5.000) = 2145 
    [ 5.000,  7.500) = 97 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      1.999 ms/op
     p(90.0000) =      2.683 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     32.014 ms/op
     p(99.9900) =     34.323 ms/op
     p(99.9990) =     34.406 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 3.118 ±(99.9%) 0.075 ms/op
Iteration   1: 1.844 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.609 ms/op
                 existUser·p0.50:   1.735 ms/op
                 existUser·p0.90:   2.306 ms/op
                 existUser·p0.95:   2.626 ms/op
                 existUser·p0.99:   3.383 ms/op
                 existUser·p0.999:  10.382 ms/op
                 existUser·p0.9999: 10.744 ms/op
                 existUser·p1.00:   10.961 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17346
  mean =      1.844 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 191 
    [ 1.250,  2.500) = 16047 
    [ 2.500,  3.750) = 1040 
    [ 3.750,  5.000) = 35 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      1.735 ms/op
     p(90.0000) =      2.306 ms/op
     p(95.0000) =      2.626 ms/op
     p(99.0000) =      3.383 ms/op
     p(99.9000) =     10.382 ms/op
     p(99.9900) =     10.744 ms/op
     p(99.9990) =     10.961 ms/op
     p(99.9999) =     10.961 ms/op
    p(100.0000) =     10.961 ms/op


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
# Warmup Iteration   1: 3.289 ±(99.9%) 0.091 ms/op
Iteration   1: 2.241 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.297 ms/op
                 getUser·p0.50:   2.146 ms/op
                 getUser·p0.90:   2.773 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  25.428 ms/op
                 getUser·p0.9999: 25.952 ms/op
                 getUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14263
  mean =      2.241 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10371 
    [ 2.500,  5.000) = 3782 
    [ 5.000,  7.500) = 47 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.297 ms/op
     p(50.0000) =      2.146 ms/op
     p(90.0000) =      2.773 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =     25.428 ms/op
     p(99.9900) =     25.952 ms/op
     p(99.9990) =     25.952 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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
# Warmup Iteration   1: 4.124 ±(99.9%) 0.125 ms/op
Iteration   1: 3.649 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.931 ms/op
                 listUser·p0.999:  11.452 ms/op
                 listUser·p0.9999: 11.747 ms/op
                 listUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8762
  mean =      3.649 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 753 
    [ 2.500,  3.750) = 3741 
    [ 3.750,  5.000) = 4037 
    [ 5.000,  6.250) = 173 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     11.452 ms/op
     p(99.9900) =     11.747 ms/op
     p(99.9990) =     11.747 ms/op
     p(99.9999) =     11.747 ms/op
    p(100.0000) =     11.747 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.252          ops/ms
ClientSimple.existUser                       thrpt         12.577          ops/ms
ClientSimple.getUser                         thrpt         13.620          ops/ms
ClientSimple.listUser                        thrpt          8.770          ops/ms
ClientSimple.createUser                       avgt          2.346           ms/op
ClientSimple.existUser                        avgt          1.861           ms/op
ClientSimple.getUser                          avgt          1.972           ms/op
ClientSimple.listUser                         avgt          3.353           ms/op
ClientSimple.createUser                     sample  14259   2.243 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.799           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.999           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.683           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.097           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.955           ms/op
ClientSimple.createUser:createUser·p0.999   sample         32.014           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         34.323           ms/op
ClientSimple.createUser:createUser·p1.00    sample         34.406           ms/op
ClientSimple.existUser                      sample  17346   1.844 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.609           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.735           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.306           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.626           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.383           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.382           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.744           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.961           ms/op
ClientSimple.getUser                        sample  14263   2.241 ± 0.036   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.297           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.146           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.773           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.129           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.334           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.428           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.952           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.952           ms/op
ClientSimple.listUser                       sample   8762   3.649 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.194           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.731           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.366           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.538           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.931           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.452           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.747           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.747           ms/op

Benchmark result is saved to 1713291048269.json
