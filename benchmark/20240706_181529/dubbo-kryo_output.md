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
# Warmup Iteration   1: 1.604 ops/ms
Iteration   1: 6.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.600 ops/ms


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
# Warmup Iteration   1: 6.173 ops/ms
Iteration   1: 12.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.494 ops/ms


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
# Warmup Iteration   1: 5.727 ops/ms
Iteration   1: 13.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.294 ops/ms


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
# Warmup Iteration   1: 5.594 ops/ms
Iteration   1: 8.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.579 ops/ms


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
# Warmup Iteration   1: 3.673 ±(99.9%) 0.085 ms/op
Iteration   1: 2.208 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.208 ms/op


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
# Warmup Iteration   1: 3.328 ±(99.9%) 0.057 ms/op
Iteration   1: 1.878 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.878 ms/op


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
# Warmup Iteration   1: 3.217 ±(99.9%) 0.063 ms/op
Iteration   1: 2.067 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.067 ms/op


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
# Warmup Iteration   1: 4.356 ±(99.9%) 0.079 ms/op
Iteration   1: 3.067 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.067 ms/op


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
# Warmup Iteration   1: 3.405 ±(99.9%) 0.083 ms/op
Iteration   1: 1.935 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.760 ms/op
                 createUser·p0.50:   1.757 ms/op
                 createUser·p0.90:   2.351 ms/op
                 createUser·p0.95:   2.630 ms/op
                 createUser·p0.99:   4.170 ms/op
                 createUser·p0.999:  37.126 ms/op
                 createUser·p0.9999: 38.601 ms/op
                 createUser·p1.00:   38.601 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16504
  mean =      1.935 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15318 
    [ 2.500,  5.000) = 1032 
    [ 5.000,  7.500) = 73 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      1.757 ms/op
     p(90.0000) =      2.351 ms/op
     p(95.0000) =      2.630 ms/op
     p(99.0000) =      4.170 ms/op
     p(99.9000) =     37.126 ms/op
     p(99.9900) =     38.601 ms/op
     p(99.9990) =     38.601 ms/op
     p(99.9999) =     38.601 ms/op
    p(100.0000) =     38.601 ms/op


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
# Warmup Iteration   1: 2.874 ±(99.9%) 0.069 ms/op
Iteration   1: 2.102 ±(99.9%) 0.038 ms/op
                 existUser·p0.00:   0.555 ms/op
                 existUser·p0.50:   1.907 ms/op
                 existUser·p0.90:   2.826 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   6.363 ms/op
                 existUser·p0.999:  26.044 ms/op
                 existUser·p0.9999: 26.410 ms/op
                 existUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15211
  mean =      2.102 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11918 
    [ 2.500,  5.000) = 3127 
    [ 5.000,  7.500) = 66 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      1.907 ms/op
     p(90.0000) =      2.826 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      6.363 ms/op
     p(99.9000) =     26.044 ms/op
     p(99.9900) =     26.410 ms/op
     p(99.9990) =     26.444 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


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
# Warmup Iteration   1: 3.360 ±(99.9%) 0.084 ms/op
Iteration   1: 1.844 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   1.726 ms/op
                 getUser·p0.90:   2.212 ms/op
                 getUser·p0.95:   2.441 ms/op
                 getUser·p0.99:   3.564 ms/op
                 getUser·p0.999:  13.244 ms/op
                 getUser·p0.9999: 14.045 ms/op
                 getUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17809
  mean =      1.844 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 98 
    [ 1.250,  2.500) = 16943 
    [ 2.500,  3.750) = 614 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      1.726 ms/op
     p(90.0000) =      2.212 ms/op
     p(95.0000) =      2.441 ms/op
     p(99.0000) =      3.564 ms/op
     p(99.9000) =     13.244 ms/op
     p(99.9900) =     14.045 ms/op
     p(99.9990) =     14.057 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


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
# Warmup Iteration   1: 4.280 ±(99.9%) 0.127 ms/op
Iteration   1: 3.055 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.112 ms/op
                 listUser·p0.50:   2.806 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.188 ms/op
                 listUser·p0.999:  7.099 ms/op
                 listUser·p0.9999: 8.644 ms/op
                 listUser·p1.00:   8.651 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10495
  mean =      3.055 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 13 
    [1.500, 2.000) = 104 
    [2.000, 2.500) = 1581 
    [2.500, 3.000) = 4983 
    [3.000, 3.500) = 1311 
    [3.500, 4.000) = 1568 
    [4.000, 4.500) = 543 
    [4.500, 5.000) = 176 
    [5.000, 5.500) = 75 
    [5.500, 6.000) = 31 
    [6.000, 6.500) = 28 
    [6.500, 7.000) = 70 
    [7.000, 7.500) = 6 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      2.806 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.188 ms/op
     p(99.9000) =      7.099 ms/op
     p(99.9900) =      8.644 ms/op
     p(99.9990) =      8.651 ms/op
     p(99.9999) =      8.651 ms/op
    p(100.0000) =      8.651 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.600          ops/ms
ClientSimple.existUser                       thrpt         12.494          ops/ms
ClientSimple.getUser                         thrpt         13.294          ops/ms
ClientSimple.listUser                        thrpt          8.579          ops/ms
ClientSimple.createUser                       avgt          2.208           ms/op
ClientSimple.existUser                        avgt          1.878           ms/op
ClientSimple.getUser                          avgt          2.067           ms/op
ClientSimple.listUser                         avgt          3.067           ms/op
ClientSimple.createUser                     sample  16504   1.935 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.760           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.757           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.351           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.630           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.170           ms/op
ClientSimple.createUser:createUser·p0.999   sample         37.126           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         38.601           ms/op
ClientSimple.createUser:createUser·p1.00    sample         38.601           ms/op
ClientSimple.existUser                      sample  15211   2.102 ± 0.038   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.555           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.907           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.826           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.105           ms/op
ClientSimple.existUser:existUser·p0.99      sample          6.363           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.044           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.410           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.444           ms/op
ClientSimple.getUser                        sample  17809   1.844 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.926           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.726           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.212           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.441           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.564           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.244           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.045           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.057           ms/op
ClientSimple.listUser                       sample  10495   3.055 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.112           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.806           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.953           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.188           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.099           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.644           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.651           ms/op

Benchmark result is saved to 1720289473021.json
