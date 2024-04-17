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
# Warmup Iteration   1: 1.621 ops/ms
Iteration   1: 6.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.515 ops/ms


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
# Warmup Iteration   1: 6.574 ops/ms
Iteration   1: 13.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.716 ops/ms


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
# Warmup Iteration   1: 6.791 ops/ms
Iteration   1: 13.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.377 ops/ms


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
# Warmup Iteration   1: 4.884 ops/ms
Iteration   1: 8.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.531 ops/ms


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
# Warmup Iteration   1: 3.670 ±(99.9%) 0.070 ms/op
Iteration   1: 2.044 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.044 ms/op


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
# Warmup Iteration   1: 2.913 ±(99.9%) 0.047 ms/op
Iteration   1: 1.900 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.900 ms/op


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
# Warmup Iteration   1: 3.209 ±(99.9%) 0.071 ms/op
Iteration   1: 2.092 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.092 ms/op


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
# Warmup Iteration   1: 4.208 ±(99.9%) 0.096 ms/op
Iteration   1: 3.222 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.222 ms/op


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
# Warmup Iteration   1: 3.393 ±(99.9%) 0.088 ms/op
Iteration   1: 2.222 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.902 ms/op
                 createUser·p0.50:   2.171 ms/op
                 createUser·p0.90:   2.777 ms/op
                 createUser·p0.95:   2.945 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  16.073 ms/op
                 createUser·p0.9999: 16.281 ms/op
                 createUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14372
  mean =      2.222 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 10603 
    [ 2.500,  3.750) = 3456 
    [ 3.750,  5.000) = 104 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      2.171 ms/op
     p(90.0000) =      2.777 ms/op
     p(95.0000) =      2.945 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =     16.073 ms/op
     p(99.9900) =     16.281 ms/op
     p(99.9990) =     16.302 ms/op
     p(99.9999) =     16.302 ms/op
    p(100.0000) =     16.302 ms/op


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
# Warmup Iteration   1: 3.146 ±(99.9%) 0.071 ms/op
Iteration   1: 1.727 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.383 ms/op
                 existUser·p0.50:   1.597 ms/op
                 existUser·p0.90:   2.044 ms/op
                 existUser·p0.95:   2.212 ms/op
                 existUser·p0.99:   2.953 ms/op
                 existUser·p0.999:  27.852 ms/op
                 existUser·p0.9999: 28.954 ms/op
                 existUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18502
  mean =      1.727 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18159 
    [ 2.500,  5.000) = 267 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.383 ms/op
     p(50.0000) =      1.597 ms/op
     p(90.0000) =      2.044 ms/op
     p(95.0000) =      2.212 ms/op
     p(99.0000) =      2.953 ms/op
     p(99.9000) =     27.852 ms/op
     p(99.9900) =     28.954 ms/op
     p(99.9990) =     29.065 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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
# Warmup Iteration   1: 3.548 ±(99.9%) 0.100 ms/op
Iteration   1: 2.250 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.686 ms/op
                 getUser·p0.50:   2.191 ms/op
                 getUser·p0.90:   2.777 ms/op
                 getUser·p0.95:   2.929 ms/op
                 getUser·p0.99:   3.609 ms/op
                 getUser·p0.999:  12.023 ms/op
                 getUser·p0.9999: 13.480 ms/op
                 getUser·p1.00:   13.615 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14581
  mean =      2.250 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 10782 
    [ 2.500,  3.750) = 3612 
    [ 3.750,  5.000) = 86 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      2.191 ms/op
     p(90.0000) =      2.777 ms/op
     p(95.0000) =      2.929 ms/op
     p(99.0000) =      3.609 ms/op
     p(99.9000) =     12.023 ms/op
     p(99.9900) =     13.480 ms/op
     p(99.9990) =     13.615 ms/op
     p(99.9999) =     13.615 ms/op
    p(100.0000) =     13.615 ms/op


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
# Warmup Iteration   1: 4.923 ±(99.9%) 0.158 ms/op
Iteration   1: 3.733 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   6.390 ms/op
                 listUser·p0.999:  7.573 ms/op
                 listUser·p0.9999: 7.627 ms/op
                 listUser·p1.00:   7.627 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8570
  mean =      3.733 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 9 
    [1.500, 2.000) = 25 
    [2.000, 2.500) = 191 
    [2.500, 3.000) = 1301 
    [3.000, 3.500) = 1663 
    [3.500, 4.000) = 2377 
    [4.000, 4.500) = 2117 
    [4.500, 5.000) = 486 
    [5.000, 5.500) = 200 
    [5.500, 6.000) = 90 
    [6.000, 6.500) = 37 
    [6.500, 7.000) = 42 
    [7.000, 7.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =      7.573 ms/op
     p(99.9900) =      7.627 ms/op
     p(99.9990) =      7.627 ms/op
     p(99.9999) =      7.627 ms/op
    p(100.0000) =      7.627 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.515          ops/ms
ClientSimple.existUser                       thrpt         13.716          ops/ms
ClientSimple.getUser                         thrpt         13.377          ops/ms
ClientSimple.listUser                        thrpt          8.531          ops/ms
ClientSimple.createUser                       avgt          2.044           ms/op
ClientSimple.existUser                        avgt          1.900           ms/op
ClientSimple.getUser                          avgt          2.092           ms/op
ClientSimple.listUser                         avgt          3.222           ms/op
ClientSimple.createUser                     sample  14372   2.222 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.902           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.171           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.777           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.945           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.252           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.073           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.281           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.302           ms/op
ClientSimple.existUser                      sample  18502   1.727 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.383           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.597           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.044           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.212           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.953           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.852           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         28.954           ms/op
ClientSimple.existUser:existUser·p1.00      sample         29.065           ms/op
ClientSimple.getUser                        sample  14581   2.250 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.686           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.191           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.777           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.929           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.609           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.023           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.480           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.615           ms/op
ClientSimple.listUser                       sample   8570   3.733 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.290           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.723           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.948           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.390           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.573           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.627           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.627           ms/op

Benchmark result is saved to 1713356108820.json
