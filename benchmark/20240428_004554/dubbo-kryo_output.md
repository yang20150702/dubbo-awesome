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
# Warmup Iteration   1: 1.529 ops/ms
Iteration   1: 6.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.544 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.788 ops/ms
Iteration   1: 12.943 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.943 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.314 ops/ms
Iteration   1: 12.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.543 ops/ms


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
# Warmup Iteration   1: 4.819 ops/ms
Iteration   1: 9.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.064 ops/ms


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
# Warmup Iteration   1: 4.609 ±(99.9%) 0.096 ms/op
Iteration   1: 2.235 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.235 ms/op


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
# Warmup Iteration   1: 3.391 ±(99.9%) 0.059 ms/op
Iteration   1: 1.859 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.859 ms/op


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
# Warmup Iteration   1: 3.580 ±(99.9%) 0.070 ms/op
Iteration   1: 1.942 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.942 ms/op


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
# Warmup Iteration   1: 4.626 ±(99.9%) 0.088 ms/op
Iteration   1: 3.466 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.466 ms/op


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
# Warmup Iteration   1: 3.594 ±(99.9%) 0.099 ms/op
Iteration   1: 2.195 ±(99.9%) 0.081 ms/op
                 createUser·p0.00:   0.524 ms/op
                 createUser·p0.50:   1.987 ms/op
                 createUser·p0.90:   2.404 ms/op
                 createUser·p0.95:   2.630 ms/op
                 createUser·p0.99:   6.367 ms/op
                 createUser·p0.999:  61.342 ms/op
                 createUser·p0.9999: 74.198 ms/op
                 createUser·p1.00:   74.318 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14560
  mean =      2.195 ±(99.9%) 0.081 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14376 
    [ 5.000, 10.000) = 88 
    [10.000, 15.000) = 27 
    [15.000, 20.000) = 34 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 2 
    [50.000, 55.000) = 2 
    [55.000, 60.000) = 3 
    [60.000, 65.000) = 16 
    [65.000, 70.000) = 4 
    [70.000, 75.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      1.987 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.630 ms/op
     p(99.0000) =      6.367 ms/op
     p(99.9000) =     61.342 ms/op
     p(99.9900) =     74.198 ms/op
     p(99.9990) =     74.318 ms/op
     p(99.9999) =     74.318 ms/op
    p(100.0000) =     74.318 ms/op


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
# Warmup Iteration   1: 3.245 ±(99.9%) 0.072 ms/op
Iteration   1: 1.807 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   1.716 ms/op
                 existUser·p0.90:   2.187 ms/op
                 existUser·p0.95:   2.372 ms/op
                 existUser·p0.99:   2.802 ms/op
                 existUser·p0.999:  12.379 ms/op
                 existUser·p0.9999: 13.640 ms/op
                 existUser·p1.00:   13.779 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17688
  mean =      1.807 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 17098 
    [ 2.500,  3.750) = 389 
    [ 3.750,  5.000) = 53 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      1.716 ms/op
     p(90.0000) =      2.187 ms/op
     p(95.0000) =      2.372 ms/op
     p(99.0000) =      2.802 ms/op
     p(99.9000) =     12.379 ms/op
     p(99.9900) =     13.640 ms/op
     p(99.9990) =     13.779 ms/op
     p(99.9999) =     13.779 ms/op
    p(100.0000) =     13.779 ms/op


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
# Warmup Iteration   1: 3.348 ±(99.9%) 0.096 ms/op
Iteration   1: 2.094 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.512 ms/op
                 getUser·p0.50:   2.044 ms/op
                 getUser·p0.90:   2.552 ms/op
                 getUser·p0.95:   2.757 ms/op
                 getUser·p0.99:   3.785 ms/op
                 getUser·p0.999:  11.551 ms/op
                 getUser·p0.9999: 12.382 ms/op
                 getUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15300
  mean =      2.094 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 204 
    [ 1.250,  2.500) = 13197 
    [ 2.500,  3.750) = 1744 
    [ 3.750,  5.000) = 82 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.512 ms/op
     p(50.0000) =      2.044 ms/op
     p(90.0000) =      2.552 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =     11.551 ms/op
     p(99.9900) =     12.382 ms/op
     p(99.9990) =     12.747 ms/op
     p(99.9999) =     12.747 ms/op
    p(100.0000) =     12.747 ms/op


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
# Warmup Iteration   1: 4.090 ±(99.9%) 0.098 ms/op
Iteration   1: 3.565 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   0.794 ms/op
                 listUser·p0.50:   3.543 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   7.458 ms/op
                 listUser·p0.999:  14.665 ms/op
                 listUser·p0.9999: 14.909 ms/op
                 listUser·p1.00:   14.909 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8990
  mean =      3.565 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 16 
    [ 1.250,  2.500) = 652 
    [ 2.500,  3.750) = 5366 
    [ 3.750,  5.000) = 2737 
    [ 5.000,  6.250) = 110 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      3.543 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      7.458 ms/op
     p(99.9000) =     14.665 ms/op
     p(99.9900) =     14.909 ms/op
     p(99.9990) =     14.909 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.544          ops/ms
ClientSimple.existUser                       thrpt         12.943          ops/ms
ClientSimple.getUser                         thrpt         12.543          ops/ms
ClientSimple.listUser                        thrpt          9.064          ops/ms
ClientSimple.createUser                       avgt          2.235           ms/op
ClientSimple.existUser                        avgt          1.859           ms/op
ClientSimple.getUser                          avgt          1.942           ms/op
ClientSimple.listUser                         avgt          3.466           ms/op
ClientSimple.createUser                     sample  14560   2.195 ± 0.081   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.524           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.987           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.404           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.630           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.367           ms/op
ClientSimple.createUser:createUser·p0.999   sample         61.342           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         74.198           ms/op
ClientSimple.createUser:createUser·p1.00    sample         74.318           ms/op
ClientSimple.existUser                      sample  17688   1.807 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.722           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.716           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.187           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.372           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.802           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.379           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.640           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.779           ms/op
ClientSimple.getUser                        sample  15300   2.094 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.512           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.044           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.552           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.757           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.785           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.551           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.382           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.747           ms/op
ClientSimple.listUser                       sample   8990   3.565 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.794           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.543           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.458           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.665           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.909           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.909           ms/op

Benchmark result is saved to 1714264887696.json
