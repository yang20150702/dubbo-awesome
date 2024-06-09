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
# Warmup Iteration   1: 1.437 ops/ms
Iteration   1: 6.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.581 ops/ms


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
# Warmup Iteration   1: 5.529 ops/ms
Iteration   1: 12.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.437 ops/ms


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
# Warmup Iteration   1: 5.320 ops/ms
Iteration   1: 12.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.898 ops/ms


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
# Warmup Iteration   1: 4.271 ops/ms
Iteration   1: 8.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.068 ops/ms


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
# Warmup Iteration   1: 4.067 ±(99.9%) 0.076 ms/op
Iteration   1: 1.994 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.430 ±(99.9%) 0.062 ms/op
Iteration   1: 1.838 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.838 ms/op


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
# Warmup Iteration   1: 3.260 ±(99.9%) 0.056 ms/op
Iteration   1: 1.923 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.923 ms/op


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
# Warmup Iteration   1: 4.800 ±(99.9%) 0.117 ms/op
Iteration   1: 3.086 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.086 ms/op


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
# Warmup Iteration   1: 3.733 ±(99.9%) 0.097 ms/op
Iteration   1: 2.174 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   0.375 ms/op
                 createUser·p0.50:   1.968 ms/op
                 createUser·p0.90:   2.527 ms/op
                 createUser·p0.95:   2.834 ms/op
                 createUser·p0.99:   13.603 ms/op
                 createUser·p0.999:  25.109 ms/op
                 createUser·p0.9999: 27.284 ms/op
                 createUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14736
  mean =      2.174 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13137 
    [ 2.500,  5.000) = 1344 
    [ 5.000,  7.500) = 71 
    [ 7.500, 10.000) = 20 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.375 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =     13.603 ms/op
     p(99.9000) =     25.109 ms/op
     p(99.9900) =     27.284 ms/op
     p(99.9990) =     27.656 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


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
# Warmup Iteration   1: 2.883 ±(99.9%) 0.063 ms/op
Iteration   1: 1.973 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.589 ms/op
                 existUser·p0.50:   1.841 ms/op
                 existUser·p0.90:   2.621 ms/op
                 existUser·p0.95:   2.798 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  13.418 ms/op
                 existUser·p0.9999: 14.326 ms/op
                 existUser·p1.00:   14.418 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16232
  mean =      1.973 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 515 
    [ 1.250,  2.500) = 13243 
    [ 2.500,  3.750) = 2318 
    [ 3.750,  5.000) = 29 
    [ 5.000,  6.250) = 84 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      1.841 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.798 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =     13.418 ms/op
     p(99.9900) =     14.326 ms/op
     p(99.9990) =     14.418 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


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
# Warmup Iteration   1: 3.780 ±(99.9%) 0.094 ms/op
Iteration   1: 2.183 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.530 ms/op
                 getUser·p0.50:   2.087 ms/op
                 getUser·p0.90:   2.634 ms/op
                 getUser·p0.95:   2.818 ms/op
                 getUser·p0.99:   4.150 ms/op
                 getUser·p0.999:  15.581 ms/op
                 getUser·p0.9999: 15.667 ms/op
                 getUser·p1.00:   15.729 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14683
  mean =      2.183 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 105 
    [ 1.250,  2.500) = 12231 
    [ 2.500,  3.750) = 2172 
    [ 3.750,  5.000) = 50 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      2.087 ms/op
     p(90.0000) =      2.634 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      4.150 ms/op
     p(99.9000) =     15.581 ms/op
     p(99.9900) =     15.667 ms/op
     p(99.9990) =     15.729 ms/op
     p(99.9999) =     15.729 ms/op
    p(100.0000) =     15.729 ms/op


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
# Warmup Iteration   1: 4.799 ±(99.9%) 0.136 ms/op
Iteration   1: 3.447 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   3.416 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   5.999 ms/op
                 listUser·p0.999:  17.072 ms/op
                 listUser·p0.9999: 17.760 ms/op
                 listUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9270
  mean =      3.447 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1644 
    [ 2.500,  3.750) = 4252 
    [ 3.750,  5.000) = 3099 
    [ 5.000,  6.250) = 201 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      5.999 ms/op
     p(99.9000) =     17.072 ms/op
     p(99.9900) =     17.760 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.581          ops/ms
ClientSimple.existUser                       thrpt         12.437          ops/ms
ClientSimple.getUser                         thrpt         12.898          ops/ms
ClientSimple.listUser                        thrpt          8.068          ops/ms
ClientSimple.createUser                       avgt          1.994           ms/op
ClientSimple.existUser                        avgt          1.838           ms/op
ClientSimple.getUser                          avgt          1.923           ms/op
ClientSimple.listUser                         avgt          3.086           ms/op
ClientSimple.createUser                     sample  14736   2.174 ± 0.049   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.375           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.968           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.527           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.834           ms/op
ClientSimple.createUser:createUser·p0.99    sample         13.603           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.109           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.284           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.656           ms/op
ClientSimple.existUser                      sample  16232   1.973 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.589           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.841           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.798           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.662           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.418           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.326           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.418           ms/op
ClientSimple.getUser                        sample  14683   2.183 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.530           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.087           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.634           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.818           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.150           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.581           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.667           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.729           ms/op
ClientSimple.listUser                       sample   9270   3.447 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.198           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.416           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.489           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.678           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.999           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.072           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.760           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.760           ms/op

Benchmark result is saved to 1717956656552.json
