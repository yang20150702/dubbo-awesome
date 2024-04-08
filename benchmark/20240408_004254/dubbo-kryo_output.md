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
# Warmup Iteration   1: 1.779 ops/ms
Iteration   1: 7.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.269 ops/ms


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
# Warmup Iteration   1: 5.873 ops/ms
Iteration   1: 13.214 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.214 ops/ms


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
# Warmup Iteration   1: 5.656 ops/ms
Iteration   1: 12.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.378 ops/ms


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
# Warmup Iteration   1: 5.267 ops/ms
Iteration   1: 8.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.224 ops/ms


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
# Warmup Iteration   1: 3.452 ±(99.9%) 0.062 ms/op
Iteration   1: 1.973 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.973 ms/op


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
# Warmup Iteration   1: 2.976 ±(99.9%) 0.047 ms/op
Iteration   1: 1.819 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.819 ms/op


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
# Warmup Iteration   1: 3.445 ±(99.9%) 0.071 ms/op
Iteration   1: 1.946 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.946 ms/op


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
# Warmup Iteration   1: 4.447 ±(99.9%) 0.088 ms/op
Iteration   1: 3.494 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.494 ms/op


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
# Warmup Iteration   1: 3.605 ±(99.9%) 0.095 ms/op
Iteration   1: 2.211 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.389 ms/op
                 createUser·p0.50:   2.085 ms/op
                 createUser·p0.90:   2.576 ms/op
                 createUser·p0.95:   2.867 ms/op
                 createUser·p0.99:   6.920 ms/op
                 createUser·p0.999:  16.655 ms/op
                 createUser·p0.9999: 16.763 ms/op
                 createUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14474
  mean =      2.211 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 205 
    [ 1.250,  2.500) = 12560 
    [ 2.500,  3.750) = 1399 
    [ 3.750,  5.000) = 117 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.389 ms/op
     p(50.0000) =      2.085 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.867 ms/op
     p(99.0000) =      6.920 ms/op
     p(99.9000) =     16.655 ms/op
     p(99.9900) =     16.763 ms/op
     p(99.9990) =     16.777 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


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
# Warmup Iteration   1: 3.057 ±(99.9%) 0.066 ms/op
Iteration   1: 2.067 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.496 ms/op
                 existUser·p0.50:   1.978 ms/op
                 existUser·p0.90:   2.449 ms/op
                 existUser·p0.95:   2.658 ms/op
                 existUser·p0.99:   3.191 ms/op
                 existUser·p0.999:  21.856 ms/op
                 existUser·p0.9999: 22.306 ms/op
                 existUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15459
  mean =      2.067 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14181 
    [ 2.500,  5.000) = 1179 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.496 ms/op
     p(50.0000) =      1.978 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.658 ms/op
     p(99.0000) =      3.191 ms/op
     p(99.9000) =     21.856 ms/op
     p(99.9900) =     22.306 ms/op
     p(99.9990) =     22.413 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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
# Warmup Iteration   1: 3.171 ±(99.9%) 0.081 ms/op
Iteration   1: 1.820 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.588 ms/op
                 getUser·p0.50:   1.739 ms/op
                 getUser·p0.90:   2.335 ms/op
                 getUser·p0.95:   2.507 ms/op
                 getUser·p0.99:   3.162 ms/op
                 getUser·p0.999:  14.114 ms/op
                 getUser·p0.9999: 15.850 ms/op
                 getUser·p1.00:   15.974 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17614
  mean =      1.820 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 778 
    [ 1.250,  2.500) = 15938 
    [ 2.500,  3.750) = 783 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      1.739 ms/op
     p(90.0000) =      2.335 ms/op
     p(95.0000) =      2.507 ms/op
     p(99.0000) =      3.162 ms/op
     p(99.9000) =     14.114 ms/op
     p(99.9900) =     15.850 ms/op
     p(99.9990) =     15.974 ms/op
     p(99.9999) =     15.974 ms/op
    p(100.0000) =     15.974 ms/op


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
# Warmup Iteration   1: 5.777 ±(99.9%) 0.527 ms/op
Iteration   1: 3.267 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   0.672 ms/op
                 listUser·p0.50:   3.228 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   6.285 ms/op
                 listUser·p0.999:  14.418 ms/op
                 listUser·p0.9999: 14.762 ms/op
                 listUser·p1.00:   14.762 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9759
  mean =      3.267 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 1403 
    [ 2.500,  3.750) = 6465 
    [ 3.750,  5.000) = 1561 
    [ 5.000,  6.250) = 219 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      6.285 ms/op
     p(99.9000) =     14.418 ms/op
     p(99.9900) =     14.762 ms/op
     p(99.9990) =     14.762 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.269          ops/ms
ClientSimple.existUser                       thrpt         13.214          ops/ms
ClientSimple.getUser                         thrpt         12.378          ops/ms
ClientSimple.listUser                        thrpt          8.224          ops/ms
ClientSimple.createUser                       avgt          1.973           ms/op
ClientSimple.existUser                        avgt          1.819           ms/op
ClientSimple.getUser                          avgt          1.946           ms/op
ClientSimple.listUser                         avgt          3.494           ms/op
ClientSimple.createUser                     sample  14474   2.211 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.389           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.085           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.576           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.867           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.920           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.655           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.763           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.777           ms/op
ClientSimple.existUser                      sample  15459   2.067 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.496           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.978           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.449           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.658           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.191           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.856           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.306           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.413           ms/op
ClientSimple.getUser                        sample  17614   1.820 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.588           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.739           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.335           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.507           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.162           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.114           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.850           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.974           ms/op
ClientSimple.listUser                       sample   9759   3.267 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.672           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.228           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.071           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.514           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.285           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.418           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.762           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.762           ms/op

Benchmark result is saved to 1712536712566.json
