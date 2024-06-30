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
# Warmup Iteration   1: 1.438 ops/ms
Iteration   1: 7.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.783 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.984 ops/ms
Iteration   1: 10.824 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.824 ops/ms


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
# Warmup Iteration   1: 4.388 ops/ms
Iteration   1: 12.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.294 ops/ms


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
# Warmup Iteration   1: 5.137 ops/ms
Iteration   1: 8.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.501 ops/ms


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
# Warmup Iteration   1: 4.716 ±(99.9%) 0.091 ms/op
Iteration   1: 2.391 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.391 ms/op


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
# Warmup Iteration   1: 3.357 ±(99.9%) 0.069 ms/op
Iteration   1: 1.986 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.986 ms/op


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
# Warmup Iteration   1: 3.458 ±(99.9%) 0.077 ms/op
Iteration   1: 2.204 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.204 ms/op


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
# Warmup Iteration   1: 4.399 ±(99.9%) 0.108 ms/op
Iteration   1: 3.304 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.304 ms/op


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
# Warmup Iteration   1: 3.527 ±(99.9%) 0.082 ms/op
Iteration   1: 2.230 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   2.036 ms/op
                 createUser·p0.90:   2.621 ms/op
                 createUser·p0.95:   2.884 ms/op
                 createUser·p0.99:   8.405 ms/op
                 createUser·p0.999:  14.717 ms/op
                 createUser·p0.9999: 20.185 ms/op
                 createUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14339
  mean =      2.230 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12208 
    [ 2.500,  5.000) = 1862 
    [ 5.000,  7.500) = 106 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      2.036 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.884 ms/op
     p(99.0000) =      8.405 ms/op
     p(99.9000) =     14.717 ms/op
     p(99.9900) =     20.185 ms/op
     p(99.9990) =     20.185 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


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
# Warmup Iteration   1: 2.797 ±(99.9%) 0.058 ms/op
Iteration   1: 1.868 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.554 ms/op
                 existUser·p0.50:   1.733 ms/op
                 existUser·p0.90:   2.359 ms/op
                 existUser·p0.95:   2.576 ms/op
                 existUser·p0.99:   3.212 ms/op
                 existUser·p0.999:  16.089 ms/op
                 existUser·p0.9999: 16.180 ms/op
                 existUser·p1.00:   16.204 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17179
  mean =      1.868 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 566 
    [ 1.250,  2.500) = 15439 
    [ 2.500,  3.750) = 1064 
    [ 3.750,  5.000) = 22 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      1.733 ms/op
     p(90.0000) =      2.359 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      3.212 ms/op
     p(99.9000) =     16.089 ms/op
     p(99.9900) =     16.180 ms/op
     p(99.9990) =     16.204 ms/op
     p(99.9999) =     16.204 ms/op
    p(100.0000) =     16.204 ms/op


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
# Warmup Iteration   1: 3.198 ±(99.9%) 0.083 ms/op
Iteration   1: 2.305 ±(99.9%) 0.094 ms/op
                 getUser·p0.00:   0.920 ms/op
                 getUser·p0.50:   2.081 ms/op
                 getUser·p0.90:   2.675 ms/op
                 getUser·p0.95:   2.966 ms/op
                 getUser·p0.99:   3.839 ms/op
                 getUser·p0.999:  71.791 ms/op
                 getUser·p0.9999: 83.886 ms/op
                 getUser·p1.00:   83.886 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13896
  mean =      2.305 ±(99.9%) 0.094 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13804 
    [ 5.000, 10.000) = 35 
    [10.000, 15.000) = 6 
    [15.000, 20.000) = 4 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 7 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 6 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 2 
    [55.000, 60.000) = 7 
    [60.000, 65.000) = 2 
    [65.000, 70.000) = 4 
    [70.000, 75.000) = 7 
    [75.000, 80.000) = 1 
    [80.000, 85.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      2.081 ms/op
     p(90.0000) =      2.675 ms/op
     p(95.0000) =      2.966 ms/op
     p(99.0000) =      3.839 ms/op
     p(99.9000) =     71.791 ms/op
     p(99.9900) =     83.886 ms/op
     p(99.9990) =     83.886 ms/op
     p(99.9999) =     83.886 ms/op
    p(100.0000) =     83.886 ms/op


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
# Warmup Iteration   1: 5.259 ±(99.9%) 0.185 ms/op
Iteration   1: 3.229 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.079 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.573 ms/op
                 listUser·p0.999:  17.760 ms/op
                 listUser·p0.9999: 19.366 ms/op
                 listUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9883
  mean =      3.229 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 1002 
    [ 2.500,  3.750) = 7255 
    [ 3.750,  5.000) = 1443 
    [ 5.000,  6.250) = 92 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.573 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     19.366 ms/op
     p(99.9990) =     19.366 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.783          ops/ms
ClientSimple.existUser                       thrpt         10.824          ops/ms
ClientSimple.getUser                         thrpt         12.294          ops/ms
ClientSimple.listUser                        thrpt          8.501          ops/ms
ClientSimple.createUser                       avgt          2.391           ms/op
ClientSimple.existUser                        avgt          1.986           ms/op
ClientSimple.getUser                          avgt          2.204           ms/op
ClientSimple.listUser                         avgt          3.304           ms/op
ClientSimple.createUser                     sample  14339   2.230 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.786           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.036           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.621           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.884           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.405           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.717           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.185           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.185           ms/op
ClientSimple.existUser                      sample  17179   1.868 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.554           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.733           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.359           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.576           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.212           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.089           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.180           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.204           ms/op
ClientSimple.getUser                        sample  13896   2.305 ± 0.094   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.920           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.081           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.675           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.966           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.839           ms/op
ClientSimple.getUser:getUser·p0.999         sample         71.791           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         83.886           ms/op
ClientSimple.getUser:getUser·p1.00          sample         83.886           ms/op
ClientSimple.listUser                       sample   9883   3.229 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.079           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.019           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.965           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.573           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.760           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.366           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.366           ms/op

Benchmark result is saved to 1719708309054.json
