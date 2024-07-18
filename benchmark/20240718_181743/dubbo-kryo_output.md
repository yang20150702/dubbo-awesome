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
# Warmup Iteration   1: 1.725 ops/ms
Iteration   1: 6.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.507 ops/ms


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
# Warmup Iteration   1: 6.683 ops/ms
Iteration   1: 11.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.596 ops/ms


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
# Warmup Iteration   1: 4.550 ops/ms
Iteration   1: 12.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.746 ops/ms


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
# Warmup Iteration   1: 4.616 ops/ms
Iteration   1: 8.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.871 ops/ms


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
# Warmup Iteration   1: 3.925 ±(99.9%) 0.070 ms/op
Iteration   1: 2.229 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.229 ms/op


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
# Warmup Iteration   1: 3.151 ±(99.9%) 0.046 ms/op
Iteration   1: 1.938 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.938 ms/op


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
# Warmup Iteration   1: 3.481 ±(99.9%) 0.088 ms/op
Iteration   1: 2.119 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.119 ms/op


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
# Warmup Iteration   1: 4.493 ±(99.9%) 0.068 ms/op
Iteration   1: 3.243 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.243 ms/op


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
# Warmup Iteration   1: 3.642 ±(99.9%) 0.090 ms/op
Iteration   1: 2.113 ±(99.9%) 0.061 ms/op
                 createUser·p0.00:   0.521 ms/op
                 createUser·p0.50:   1.876 ms/op
                 createUser·p0.90:   2.462 ms/op
                 createUser·p0.95:   2.707 ms/op
                 createUser·p0.99:   7.071 ms/op
                 createUser·p0.999:  44.881 ms/op
                 createUser·p0.9999: 47.706 ms/op
                 createUser·p1.00:   47.776 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15295
  mean =      2.113 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15040 
    [ 5.000, 10.000) = 190 
    [10.000, 15.000) = 1 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 30 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      7.071 ms/op
     p(99.9000) =     44.881 ms/op
     p(99.9900) =     47.706 ms/op
     p(99.9990) =     47.776 ms/op
     p(99.9999) =     47.776 ms/op
    p(100.0000) =     47.776 ms/op


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
# Warmup Iteration   1: 3.052 ±(99.9%) 0.077 ms/op
Iteration   1: 1.928 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.560 ms/op
                 existUser·p0.50:   1.860 ms/op
                 existUser·p0.90:   2.343 ms/op
                 existUser·p0.95:   2.494 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  14.572 ms/op
                 existUser·p0.9999: 15.407 ms/op
                 existUser·p1.00:   15.417 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16593
  mean =      1.928 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 373 
    [ 1.250,  2.500) = 15422 
    [ 2.500,  3.750) = 592 
    [ 3.750,  5.000) = 81 
    [ 5.000,  6.250) = 92 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      1.860 ms/op
     p(90.0000) =      2.343 ms/op
     p(95.0000) =      2.494 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =     14.572 ms/op
     p(99.9900) =     15.407 ms/op
     p(99.9990) =     15.417 ms/op
     p(99.9999) =     15.417 ms/op
    p(100.0000) =     15.417 ms/op


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
# Warmup Iteration   1: 3.672 ±(99.9%) 0.104 ms/op
Iteration   1: 2.143 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   2.032 ms/op
                 getUser·p0.90:   2.608 ms/op
                 getUser·p0.95:   2.818 ms/op
                 getUser·p0.99:   3.543 ms/op
                 getUser·p0.999:  11.010 ms/op
                 getUser·p0.9999: 11.117 ms/op
                 getUser·p1.00:   11.125 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14921
  mean =      2.143 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 12758 
    [ 2.500,  3.750) = 1999 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      2.032 ms/op
     p(90.0000) =      2.608 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      3.543 ms/op
     p(99.9000) =     11.010 ms/op
     p(99.9900) =     11.117 ms/op
     p(99.9990) =     11.125 ms/op
     p(99.9999) =     11.125 ms/op
    p(100.0000) =     11.125 ms/op


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
# Warmup Iteration   1: 4.710 ±(99.9%) 0.150 ms/op
Iteration   1: 3.246 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   0.744 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   6.760 ms/op
                 listUser·p0.999:  21.070 ms/op
                 listUser·p0.9999: 21.168 ms/op
                 listUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9874
  mean =      3.246 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1416 
    [ 2.500,  5.000) = 8247 
    [ 5.000,  7.500) = 143 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.760 ms/op
     p(99.9000) =     21.070 ms/op
     p(99.9900) =     21.168 ms/op
     p(99.9990) =     21.168 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.507          ops/ms
ClientSimple.existUser                       thrpt         11.596          ops/ms
ClientSimple.getUser                         thrpt         12.746          ops/ms
ClientSimple.listUser                        thrpt          8.871          ops/ms
ClientSimple.createUser                       avgt          2.229           ms/op
ClientSimple.existUser                        avgt          1.938           ms/op
ClientSimple.getUser                          avgt          2.119           ms/op
ClientSimple.listUser                         avgt          3.243           ms/op
ClientSimple.createUser                     sample  15295   2.113 ± 0.061   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.521           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.876           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.462           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.707           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.071           ms/op
ClientSimple.createUser:createUser·p0.999   sample         44.881           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         47.706           ms/op
ClientSimple.createUser:createUser·p1.00    sample         47.776           ms/op
ClientSimple.existUser                      sample  16593   1.928 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.560           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.860           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.343           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.494           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.358           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.572           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.407           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.417           ms/op
ClientSimple.getUser                        sample  14921   2.143 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.905           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.032           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.608           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.818           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.543           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.010           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.117           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.125           ms/op
ClientSimple.listUser                       sample   9874   3.246 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.744           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.015           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.125           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.760           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.070           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.168           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.168           ms/op

Benchmark result is saved to 1721326398690.json
