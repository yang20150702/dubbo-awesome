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
# Warmup Iteration   1: 1.662 ops/ms
Iteration   1: 7.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.732 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.043 ops/ms
Iteration   1: 12.081 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.081 ops/ms


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
# Warmup Iteration   1: 5.715 ops/ms
Iteration   1: 12.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.450 ops/ms


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
# Warmup Iteration   1: 5.455 ops/ms
Iteration   1: 9.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.104 ops/ms


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
# Warmup Iteration   1: 4.013 ±(99.9%) 0.072 ms/op
Iteration   1: 2.020 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.020 ms/op


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
# Warmup Iteration   1: 3.314 ±(99.9%) 0.052 ms/op
Iteration   1: 1.807 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.807 ms/op


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
# Warmup Iteration   1: 3.201 ±(99.9%) 0.060 ms/op
Iteration   1: 2.101 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.101 ms/op


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
# Warmup Iteration   1: 4.332 ±(99.9%) 0.089 ms/op
Iteration   1: 3.481 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.481 ms/op


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
# Warmup Iteration   1: 3.546 ±(99.9%) 0.116 ms/op
Iteration   1: 2.366 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.506 ms/op
                 createUser·p0.50:   2.142 ms/op
                 createUser·p0.90:   2.753 ms/op
                 createUser·p0.95:   3.056 ms/op
                 createUser·p0.99:   8.989 ms/op
                 createUser·p0.999:  18.514 ms/op
                 createUser·p0.9999: 19.372 ms/op
                 createUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13633
  mean =      2.366 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 214 
    [ 1.250,  2.500) = 10320 
    [ 2.500,  3.750) = 2650 
    [ 3.750,  5.000) = 116 
    [ 5.000,  6.250) = 95 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      2.142 ms/op
     p(90.0000) =      2.753 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      8.989 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     19.372 ms/op
     p(99.9990) =     19.431 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


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
# Warmup Iteration   1: 3.048 ±(99.9%) 0.081 ms/op
Iteration   1: 1.838 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.528 ms/op
                 existUser·p0.50:   1.763 ms/op
                 existUser·p0.90:   2.154 ms/op
                 existUser·p0.95:   2.290 ms/op
                 existUser·p0.99:   2.994 ms/op
                 existUser·p0.999:  23.167 ms/op
                 existUser·p0.9999: 23.822 ms/op
                 existUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17548
  mean =      1.838 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17098 
    [ 2.500,  5.000) = 337 
    [ 5.000,  7.500) = 43 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      1.763 ms/op
     p(90.0000) =      2.154 ms/op
     p(95.0000) =      2.290 ms/op
     p(99.0000) =      2.994 ms/op
     p(99.9000) =     23.167 ms/op
     p(99.9900) =     23.822 ms/op
     p(99.9990) =     23.822 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


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
# Warmup Iteration   1: 3.329 ±(99.9%) 0.086 ms/op
Iteration   1: 1.899 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.438 ms/op
                 getUser·p0.50:   1.702 ms/op
                 getUser·p0.90:   2.552 ms/op
                 getUser·p0.95:   2.822 ms/op
                 getUser·p0.99:   3.346 ms/op
                 getUser·p0.999:  14.746 ms/op
                 getUser·p0.9999: 14.898 ms/op
                 getUser·p1.00:   14.909 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16829
  mean =      1.899 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 111 
    [ 1.250,  2.500) = 14884 
    [ 2.500,  3.750) = 1773 
    [ 3.750,  5.000) = 17 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.438 ms/op
     p(50.0000) =      1.702 ms/op
     p(90.0000) =      2.552 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      3.346 ms/op
     p(99.9000) =     14.746 ms/op
     p(99.9900) =     14.898 ms/op
     p(99.9990) =     14.909 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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
# Warmup Iteration   1: 4.470 ±(99.9%) 0.131 ms/op
Iteration   1: 3.610 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   0.922 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   5.779 ms/op
                 listUser·p0.999:  13.092 ms/op
                 listUser·p0.9999: 13.189 ms/op
                 listUser·p1.00:   13.189 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8952
  mean =      3.610 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 19 
    [ 1.250,  2.500) = 1072 
    [ 2.500,  3.750) = 3785 
    [ 3.750,  5.000) = 3772 
    [ 5.000,  6.250) = 244 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      5.779 ms/op
     p(99.9000) =     13.092 ms/op
     p(99.9900) =     13.189 ms/op
     p(99.9990) =     13.189 ms/op
     p(99.9999) =     13.189 ms/op
    p(100.0000) =     13.189 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.732          ops/ms
ClientSimple.existUser                       thrpt         12.081          ops/ms
ClientSimple.getUser                         thrpt         12.450          ops/ms
ClientSimple.listUser                        thrpt          9.104          ops/ms
ClientSimple.createUser                       avgt          2.020           ms/op
ClientSimple.existUser                        avgt          1.807           ms/op
ClientSimple.getUser                          avgt          2.101           ms/op
ClientSimple.listUser                         avgt          3.481           ms/op
ClientSimple.createUser                     sample  13633   2.366 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.506           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.142           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.753           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.056           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.989           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.514           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.372           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.431           ms/op
ClientSimple.existUser                      sample  17548   1.838 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.528           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.763           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.154           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.290           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.994           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.167           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.822           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.822           ms/op
ClientSimple.getUser                        sample  16829   1.899 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.438           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.702           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.552           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.822           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.346           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.746           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.898           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.909           ms/op
ClientSimple.listUser                       sample   8952   3.610 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.922           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.670           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.571           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.850           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.779           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.092           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.189           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.189           ms/op

Benchmark result is saved to 1712060106532.json
