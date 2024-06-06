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
# Warmup Iteration   1: 1.729 ops/ms
Iteration   1: 7.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.165 ops/ms


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
# Warmup Iteration   1: 5.546 ops/ms
Iteration   1: 12.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.657 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.016 ops/ms
Iteration   1: 11.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.569 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.892 ops/ms
Iteration   1: 7.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.444 ops/ms


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
# Warmup Iteration   1: 4.400 ±(99.9%) 0.083 ms/op
Iteration   1: 2.278 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.278 ms/op


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
# Warmup Iteration   1: 3.052 ±(99.9%) 0.063 ms/op
Iteration   1: 1.949 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.949 ms/op


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
# Warmup Iteration   1: 3.592 ±(99.9%) 0.057 ms/op
Iteration   1: 1.994 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.994 ms/op


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
# Warmup Iteration   1: 4.678 ±(99.9%) 0.102 ms/op
Iteration   1: 3.825 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.825 ms/op


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
# Warmup Iteration   1: 3.526 ±(99.9%) 0.088 ms/op
Iteration   1: 2.074 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.685 ms/op
                 createUser·p0.50:   1.989 ms/op
                 createUser·p0.90:   2.470 ms/op
                 createUser·p0.95:   2.638 ms/op
                 createUser·p0.99:   3.572 ms/op
                 createUser·p0.999:  16.457 ms/op
                 createUser·p0.9999: 17.727 ms/op
                 createUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15413
  mean =      2.074 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 13933 
    [ 2.500,  3.750) = 1206 
    [ 3.750,  5.000) = 30 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      1.989 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      3.572 ms/op
     p(99.9000) =     16.457 ms/op
     p(99.9900) =     17.727 ms/op
     p(99.9990) =     17.727 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 3.165 ±(99.9%) 0.100 ms/op
Iteration   1: 1.877 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.501 ms/op
                 existUser·p0.50:   1.669 ms/op
                 existUser·p0.90:   2.507 ms/op
                 existUser·p0.95:   2.798 ms/op
                 existUser·p0.99:   3.314 ms/op
                 existUser·p0.999:  16.187 ms/op
                 existUser·p0.9999: 16.438 ms/op
                 existUser·p1.00:   16.450 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16922
  mean =      1.877 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 620 
    [ 1.250,  2.500) = 14572 
    [ 2.500,  3.750) = 1621 
    [ 3.750,  5.000) = 12 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      1.669 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.798 ms/op
     p(99.0000) =      3.314 ms/op
     p(99.9000) =     16.187 ms/op
     p(99.9900) =     16.438 ms/op
     p(99.9990) =     16.450 ms/op
     p(99.9999) =     16.450 ms/op
    p(100.0000) =     16.450 ms/op


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
# Warmup Iteration   1: 3.261 ±(99.9%) 0.078 ms/op
Iteration   1: 2.010 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.456 ms/op
                 getUser·p0.50:   1.901 ms/op
                 getUser·p0.90:   2.564 ms/op
                 getUser·p0.95:   2.802 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  12.386 ms/op
                 getUser·p0.9999: 12.994 ms/op
                 getUser·p1.00:   13.730 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15905
  mean =      2.010 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 247 
    [ 1.250,  2.500) = 13694 
    [ 2.500,  3.750) = 1711 
    [ 3.750,  5.000) = 170 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.456 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =     12.386 ms/op
     p(99.9900) =     12.994 ms/op
     p(99.9990) =     13.730 ms/op
     p(99.9999) =     13.730 ms/op
    p(100.0000) =     13.730 ms/op


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
# Warmup Iteration   1: 4.584 ±(99.9%) 0.138 ms/op
Iteration   1: 3.867 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   6.312 ms/op
                 listUser·p0.999:  17.301 ms/op
                 listUser·p0.9999: 21.004 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8351
  mean =      3.867 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 371 
    [ 2.500,  5.000) = 7579 
    [ 5.000,  7.500) = 328 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      6.312 ms/op
     p(99.9000) =     17.301 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     21.004 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.165          ops/ms
ClientSimple.existUser                       thrpt         12.657          ops/ms
ClientSimple.getUser                         thrpt         11.569          ops/ms
ClientSimple.listUser                        thrpt          7.444          ops/ms
ClientSimple.createUser                       avgt          2.278           ms/op
ClientSimple.existUser                        avgt          1.949           ms/op
ClientSimple.getUser                          avgt          1.994           ms/op
ClientSimple.listUser                         avgt          3.825           ms/op
ClientSimple.createUser                     sample  15413   2.074 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.685           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.989           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.470           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.638           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.572           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.457           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.727           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.727           ms/op
ClientSimple.existUser                      sample  16922   1.877 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.501           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.669           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.507           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.798           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.314           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.187           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.438           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.450           ms/op
ClientSimple.getUser                        sample  15905   2.010 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.456           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.901           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.564           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.802           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.309           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.386           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.994           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.730           ms/op
ClientSimple.listUser                       sample   8351   3.867 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.090           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.863           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.637           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.973           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.312           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.301           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.004           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.004           ms/op

Benchmark result is saved to 1717654385124.json
