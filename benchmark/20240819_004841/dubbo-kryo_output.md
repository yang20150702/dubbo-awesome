# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.761 ops/ms
Iteration   1: 6.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.330 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.115 ops/ms
Iteration   1: 11.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.061 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.065 ops/ms
Iteration   1: 10.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.445 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.865 ops/ms
Iteration   1: 7.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.837 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.250 ±(99.9%) 0.089 ms/op
Iteration   1: 2.429 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.429 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.364 ±(99.9%) 0.060 ms/op
Iteration   1: 2.093 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.093 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.346 ±(99.9%) 0.080 ms/op
Iteration   1: 2.608 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.608 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.617 ±(99.9%) 0.119 ms/op
Iteration   1: 3.528 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.528 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.947 ±(99.9%) 0.114 ms/op
Iteration   1: 2.406 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.634 ms/op
                 createUser·p0.50:   2.175 ms/op
                 createUser·p0.90:   2.953 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   9.404 ms/op
                 createUser·p0.999:  22.446 ms/op
                 createUser·p0.9999: 23.343 ms/op
                 createUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13280
  mean =      2.406 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9821 
    [ 2.500,  5.000) = 3196 
    [ 5.000,  7.500) = 101 
    [ 7.500, 10.000) = 50 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      2.175 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      9.404 ms/op
     p(99.9000) =     22.446 ms/op
     p(99.9900) =     23.343 ms/op
     p(99.9990) =     23.396 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.281 ±(99.9%) 0.106 ms/op
Iteration   1: 2.110 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   1.989 ms/op
                 existUser·p0.90:   2.613 ms/op
                 existUser·p0.95:   2.888 ms/op
                 existUser·p0.99:   4.510 ms/op
                 existUser·p0.999:  13.107 ms/op
                 existUser·p0.9999: 13.262 ms/op
                 existUser·p1.00:   13.287 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15145
  mean =      2.110 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 112 
    [ 1.250,  2.500) = 12858 
    [ 2.500,  3.750) = 1906 
    [ 3.750,  5.000) = 134 
    [ 5.000,  6.250) = 71 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      1.989 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      2.888 ms/op
     p(99.0000) =      4.510 ms/op
     p(99.9000) =     13.107 ms/op
     p(99.9900) =     13.262 ms/op
     p(99.9990) =     13.287 ms/op
     p(99.9999) =     13.287 ms/op
    p(100.0000) =     13.287 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.667 ±(99.9%) 0.126 ms/op
Iteration   1: 2.493 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   1.004 ms/op
                 getUser·p0.50:   2.372 ms/op
                 getUser·p0.90:   3.334 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   5.547 ms/op
                 getUser·p0.999:  10.797 ms/op
                 getUser·p0.9999: 11.017 ms/op
                 getUser·p1.00:   11.026 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 12884
  mean =      2.493 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 21 
    [ 1.250,  2.500) = 7299 
    [ 2.500,  3.750) = 4976 
    [ 3.750,  5.000) = 414 
    [ 5.000,  6.250) = 92 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.004 ms/op
     p(50.0000) =      2.372 ms/op
     p(90.0000) =      3.334 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      5.547 ms/op
     p(99.9000) =     10.797 ms/op
     p(99.9900) =     11.017 ms/op
     p(99.9990) =     11.026 ms/op
     p(99.9999) =     11.026 ms/op
    p(100.0000) =     11.026 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.545 ±(99.9%) 0.140 ms/op
Iteration   1: 3.973 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   10.191 ms/op
                 listUser·p0.999:  11.189 ms/op
                 listUser·p0.9999: 11.993 ms/op
                 listUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8048
  mean =      3.973 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 450 
    [ 2.500,  3.750) = 3264 
    [ 3.750,  5.000) = 3196 
    [ 5.000,  6.250) = 881 
    [ 6.250,  7.500) = 125 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =     10.191 ms/op
     p(99.9000) =     11.189 ms/op
     p(99.9900) =     11.993 ms/op
     p(99.9990) =     11.993 ms/op
     p(99.9999) =     11.993 ms/op
    p(100.0000) =     11.993 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.330          ops/ms
ClientSimple.existUser                       thrpt         11.061          ops/ms
ClientSimple.getUser                         thrpt         10.445          ops/ms
ClientSimple.listUser                        thrpt          7.837          ops/ms
ClientSimple.createUser                       avgt          2.429           ms/op
ClientSimple.existUser                        avgt          2.093           ms/op
ClientSimple.getUser                          avgt          2.608           ms/op
ClientSimple.listUser                         avgt          3.528           ms/op
ClientSimple.createUser                     sample  13280   2.406 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.634           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.175           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.953           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.240           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.404           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.446           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.343           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.396           ms/op
ClientSimple.existUser                      sample  15145   2.110 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.788           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.989           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.613           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.888           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.510           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.107           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.262           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.287           ms/op
ClientSimple.getUser                        sample  12884   2.493 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          1.004           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.372           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.334           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.645           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.547           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.797           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.017           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.026           ms/op
ClientSimple.listUser                       sample   8048   3.973 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.280           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.854           ms/op
ClientSimple.listUser:listUser·p0.90        sample          5.333           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.636           ms/op
ClientSimple.listUser:listUser·p0.99        sample         10.191           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.189           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.993           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.993           ms/op

Benchmark result is saved to 1724028257986.json
