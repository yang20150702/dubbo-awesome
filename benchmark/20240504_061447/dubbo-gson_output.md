# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.110 ops/ms
Iteration   1: 2.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.220 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.565 ops/ms
Iteration   1: 6.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  6.421 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.468 ops/ms
Iteration   1: 4.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  4.025 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.006 ops/ms
Iteration   1: 2.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.728 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 11.609 ±(99.9%) 0.428 ms/op
Iteration   1: 7.325 ±(99.9%) 0.080 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.325 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.071 ±(99.9%) 0.076 ms/op
Iteration   1: 3.394 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  3.394 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.144 ±(99.9%) 0.214 ms/op
Iteration   1: 6.906 ±(99.9%) 0.045 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  6.906 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.977 ±(99.9%) 0.425 ms/op
Iteration   1: 10.545 ±(99.9%) 0.100 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  10.545 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.462 ±(99.9%) 0.271 ms/op
Iteration   1: 7.811 ±(99.9%) 0.195 ms/op
                 createUser·p0.00:   3.813 ms/op
                 createUser·p0.50:   6.717 ms/op
                 createUser·p0.90:   10.584 ms/op
                 createUser·p0.95:   16.302 ms/op
                 createUser·p0.99:   21.997 ms/op
                 createUser·p0.999:  37.159 ms/op
                 createUser·p0.9999: 39.387 ms/op
                 createUser·p1.00:   39.387 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 4170
  mean =      7.811 ±(99.9%) 0.195 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 142 
    [ 5.000,  7.500) = 2841 
    [ 7.500, 10.000) = 706 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      3.813 ms/op
     p(50.0000) =      6.717 ms/op
     p(90.0000) =     10.584 ms/op
     p(95.0000) =     16.302 ms/op
     p(99.0000) =     21.997 ms/op
     p(99.9000) =     37.159 ms/op
     p(99.9900) =     39.387 ms/op
     p(99.9990) =     39.387 ms/op
     p(99.9999) =     39.387 ms/op
    p(100.0000) =     39.387 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.449 ±(99.9%) 0.122 ms/op
Iteration   1: 3.163 ±(99.9%) 0.055 ms/op
                 existUser·p0.00:   1.210 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   12.333 ms/op
                 existUser·p0.999:  21.180 ms/op
                 existUser·p0.9999: 23.126 ms/op
                 existUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 10127
  mean =      3.163 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1924 
    [ 2.500,  5.000) = 7932 
    [ 5.000,  7.500) = 141 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.210 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =     12.333 ms/op
     p(99.9000) =     21.180 ms/op
     p(99.9900) =     23.126 ms/op
     p(99.9990) =     23.134 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 11.113 ±(99.9%) 0.375 ms/op
Iteration   1: 6.474 ±(99.9%) 0.070 ms/op
                 getUser·p0.00:   1.714 ms/op
                 getUser·p0.50:   6.431 ms/op
                 getUser·p0.90:   8.389 ms/op
                 getUser·p0.95:   9.189 ms/op
                 getUser·p0.99:   10.820 ms/op
                 getUser·p0.999:  12.652 ms/op
                 getUser·p0.9999: 13.320 ms/op
                 getUser·p1.00:   13.320 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 4962
  mean =      6.474 ±(99.9%) 0.070 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 6 
    [ 2.500,  3.750) = 83 
    [ 3.750,  5.000) = 759 
    [ 5.000,  6.250) = 1322 
    [ 6.250,  7.500) = 1743 
    [ 7.500,  8.750) = 672 
    [ 8.750, 10.000) = 292 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.714 ms/op
     p(50.0000) =      6.431 ms/op
     p(90.0000) =      8.389 ms/op
     p(95.0000) =      9.189 ms/op
     p(99.0000) =     10.820 ms/op
     p(99.9000) =     12.652 ms/op
     p(99.9900) =     13.320 ms/op
     p(99.9990) =     13.320 ms/op
     p(99.9999) =     13.320 ms/op
    p(100.0000) =     13.320 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 13.012 ±(99.9%) 0.451 ms/op
Iteration   1: 10.833 ±(99.9%) 0.180 ms/op
                 listUser·p0.00:   3.498 ms/op
                 listUser·p0.50:   10.600 ms/op
                 listUser·p0.90:   13.582 ms/op
                 listUser·p0.95:   14.418 ms/op
                 listUser·p0.99:   26.574 ms/op
                 listUser·p0.999:  30.044 ms/op
                 listUser·p0.9999: 30.900 ms/op
                 listUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 2950
  mean =     10.833 ±(99.9%) 0.180 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 11 
    [ 5.000,  7.500) = 192 
    [ 7.500, 10.000) = 981 
    [10.000, 12.500) = 1071 
    [12.500, 15.000) = 569 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.498 ms/op
     p(50.0000) =     10.600 ms/op
     p(90.0000) =     13.582 ms/op
     p(95.0000) =     14.418 ms/op
     p(99.0000) =     26.574 ms/op
     p(99.9000) =     30.044 ms/op
     p(99.9900) =     30.900 ms/op
     p(99.9990) =     30.900 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          2.220          ops/ms
ClientSimple.existUser                       thrpt          6.421          ops/ms
ClientSimple.getUser                         thrpt          4.025          ops/ms
ClientSimple.listUser                        thrpt          2.728          ops/ms
ClientSimple.createUser                       avgt          7.325           ms/op
ClientSimple.existUser                        avgt          3.394           ms/op
ClientSimple.getUser                          avgt          6.906           ms/op
ClientSimple.listUser                         avgt         10.545           ms/op
ClientSimple.createUser                     sample   4170   7.811 ± 0.195   ms/op
ClientSimple.createUser:createUser·p0.00    sample          3.813           ms/op
ClientSimple.createUser:createUser·p0.50    sample          6.717           ms/op
ClientSimple.createUser:createUser·p0.90    sample         10.584           ms/op
ClientSimple.createUser:createUser·p0.95    sample         16.302           ms/op
ClientSimple.createUser:createUser·p0.99    sample         21.997           ms/op
ClientSimple.createUser:createUser·p0.999   sample         37.159           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         39.387           ms/op
ClientSimple.createUser:createUser·p1.00    sample         39.387           ms/op
ClientSimple.existUser                      sample  10127   3.163 ± 0.055   ms/op
ClientSimple.existUser:existUser·p0.00      sample          1.210           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.839           ms/op
ClientSimple.existUser:existUser·p0.90      sample          3.826           ms/op
ClientSimple.existUser:existUser·p0.95      sample          4.260           ms/op
ClientSimple.existUser:existUser·p0.99      sample         12.333           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.180           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.126           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.134           ms/op
ClientSimple.getUser                        sample   4962   6.474 ± 0.070   ms/op
ClientSimple.getUser:getUser·p0.00          sample          1.714           ms/op
ClientSimple.getUser:getUser·p0.50          sample          6.431           ms/op
ClientSimple.getUser:getUser·p0.90          sample          8.389           ms/op
ClientSimple.getUser:getUser·p0.95          sample          9.189           ms/op
ClientSimple.getUser:getUser·p0.99          sample         10.820           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.652           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.320           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.320           ms/op
ClientSimple.listUser                       sample   2950  10.833 ± 0.180   ms/op
ClientSimple.listUser:listUser·p0.00        sample          3.498           ms/op
ClientSimple.listUser:listUser·p0.50        sample         10.600           ms/op
ClientSimple.listUser:listUser·p0.90        sample         13.582           ms/op
ClientSimple.listUser:listUser·p0.95        sample         14.418           ms/op
ClientSimple.listUser:listUser·p0.99        sample         26.574           ms/op
ClientSimple.listUser:listUser·p0.999       sample         30.044           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         30.900           ms/op
ClientSimple.listUser:listUser·p1.00        sample         30.900           ms/op

Benchmark result is saved to 1714803027517.json
