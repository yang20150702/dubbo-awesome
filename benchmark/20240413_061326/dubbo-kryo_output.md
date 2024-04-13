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
# Warmup Iteration   1: 1.153 ops/ms
Iteration   1: 6.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.374 ops/ms


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
# Warmup Iteration   1: 6.368 ops/ms
Iteration   1: 12.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.518 ops/ms


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
# Warmup Iteration   1: 6.529 ops/ms
Iteration   1: 13.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.491 ops/ms


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
# Warmup Iteration   1: 4.176 ops/ms
Iteration   1: 9.233 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.233 ops/ms


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
# Warmup Iteration   1: 3.654 ±(99.9%) 0.069 ms/op
Iteration   1: 2.176 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.176 ms/op


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
# Warmup Iteration   1: 2.927 ±(99.9%) 0.045 ms/op
Iteration   1: 1.849 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.849 ms/op


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
# Warmup Iteration   1: 3.527 ±(99.9%) 0.090 ms/op
Iteration   1: 2.268 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.268 ms/op


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
# Warmup Iteration   1: 4.286 ±(99.9%) 0.082 ms/op
Iteration   1: 3.327 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.327 ms/op


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
# Warmup Iteration   1: 3.469 ±(99.9%) 0.094 ms/op
Iteration   1: 2.215 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   1.026 ms/op
                 createUser·p0.50:   2.062 ms/op
                 createUser·p0.90:   2.728 ms/op
                 createUser·p0.95:   2.953 ms/op
                 createUser·p0.99:   3.453 ms/op
                 createUser·p0.999:  35.717 ms/op
                 createUser·p0.9999: 37.430 ms/op
                 createUser·p1.00:   38.011 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14430
  mean =      2.215 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11991 
    [ 2.500,  5.000) = 2403 
    [ 5.000,  7.500) = 4 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.026 ms/op
     p(50.0000) =      2.062 ms/op
     p(90.0000) =      2.728 ms/op
     p(95.0000) =      2.953 ms/op
     p(99.0000) =      3.453 ms/op
     p(99.9000) =     35.717 ms/op
     p(99.9900) =     37.430 ms/op
     p(99.9990) =     38.011 ms/op
     p(99.9999) =     38.011 ms/op
    p(100.0000) =     38.011 ms/op


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
# Warmup Iteration   1: 3.108 ±(99.9%) 0.083 ms/op
Iteration   1: 2.151 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.386 ms/op
                 existUser·p0.50:   2.046 ms/op
                 existUser·p0.90:   2.757 ms/op
                 existUser·p0.95:   2.968 ms/op
                 existUser·p0.99:   4.246 ms/op
                 existUser·p0.999:  15.733 ms/op
                 existUser·p0.9999: 16.392 ms/op
                 existUser·p1.00:   16.400 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14867
  mean =      2.151 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 271 
    [ 1.250,  2.500) = 11831 
    [ 2.500,  3.750) = 2595 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.386 ms/op
     p(50.0000) =      2.046 ms/op
     p(90.0000) =      2.757 ms/op
     p(95.0000) =      2.968 ms/op
     p(99.0000) =      4.246 ms/op
     p(99.9000) =     15.733 ms/op
     p(99.9900) =     16.392 ms/op
     p(99.9990) =     16.400 ms/op
     p(99.9999) =     16.400 ms/op
    p(100.0000) =     16.400 ms/op


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
# Warmup Iteration   1: 3.309 ±(99.9%) 0.094 ms/op
Iteration   1: 2.236 ±(99.9%) 0.059 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   2.015 ms/op
                 getUser·p0.90:   2.527 ms/op
                 getUser·p0.95:   2.806 ms/op
                 getUser·p0.99:   4.917 ms/op
                 getUser·p0.999:  49.966 ms/op
                 getUser·p0.9999: 56.347 ms/op
                 getUser·p1.00:   56.558 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14580
  mean =      2.236 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14438 
    [ 5.000, 10.000) = 65 
    [10.000, 15.000) = 35 
    [15.000, 20.000) = 2 
    [20.000, 25.000) = 5 
    [25.000, 30.000) = 7 
    [30.000, 35.000) = 5 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 3 
    [45.000, 50.000) = 5 
    [50.000, 55.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      2.015 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.806 ms/op
     p(99.0000) =      4.917 ms/op
     p(99.9000) =     49.966 ms/op
     p(99.9900) =     56.347 ms/op
     p(99.9990) =     56.558 ms/op
     p(99.9999) =     56.558 ms/op
    p(100.0000) =     56.558 ms/op


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
# Warmup Iteration   1: 4.508 ±(99.9%) 0.128 ms/op
Iteration   1: 3.633 ±(99.9%) 0.049 ms/op
                 listUser·p0.00:   0.961 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   5.914 ms/op
                 listUser·p0.999:  23.854 ms/op
                 listUser·p0.9999: 24.805 ms/op
                 listUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8805
  mean =      3.633 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 328 
    [ 2.500,  5.000) = 8290 
    [ 5.000,  7.500) = 152 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      5.914 ms/op
     p(99.9000) =     23.854 ms/op
     p(99.9900) =     24.805 ms/op
     p(99.9990) =     24.805 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.374          ops/ms
ClientSimple.existUser                       thrpt         12.518          ops/ms
ClientSimple.getUser                         thrpt         13.491          ops/ms
ClientSimple.listUser                        thrpt          9.233          ops/ms
ClientSimple.createUser                       avgt          2.176           ms/op
ClientSimple.existUser                        avgt          1.849           ms/op
ClientSimple.getUser                          avgt          2.268           ms/op
ClientSimple.listUser                         avgt          3.327           ms/op
ClientSimple.createUser                     sample  14430   2.215 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.026           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.062           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.728           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.953           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.453           ms/op
ClientSimple.createUser:createUser·p0.999   sample         35.717           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         37.430           ms/op
ClientSimple.createUser:createUser·p1.00    sample         38.011           ms/op
ClientSimple.existUser                      sample  14867   2.151 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.386           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.046           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.757           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.968           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.246           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.733           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.392           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.400           ms/op
ClientSimple.getUser                        sample  14580   2.236 ± 0.059   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.870           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.015           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.527           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.806           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.917           ms/op
ClientSimple.getUser:getUser·p0.999         sample         49.966           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         56.347           ms/op
ClientSimple.getUser:getUser·p1.00          sample         56.558           ms/op
ClientSimple.listUser                       sample   8805   3.633 ± 0.049   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.961           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.629           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.661           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.914           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.854           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.805           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.805           ms/op

Benchmark result is saved to 1712988554739.json
