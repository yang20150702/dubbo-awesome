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
# Warmup Iteration   1: 1.761 ops/ms
Iteration   1: 6.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.793 ops/ms


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
# Warmup Iteration   1: 5.549 ops/ms
Iteration   1: 13.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.687 ops/ms


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
# Warmup Iteration   1: 5.420 ops/ms
Iteration   1: 10.495 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.495 ops/ms


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
# Warmup Iteration   1: 4.692 ops/ms
Iteration   1: 8.184 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.184 ops/ms


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
# Warmup Iteration   1: 3.922 ±(99.9%) 0.069 ms/op
Iteration   1: 2.205 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.205 ms/op


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
# Warmup Iteration   1: 3.490 ±(99.9%) 0.058 ms/op
Iteration   1: 1.923 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.552 ±(99.9%) 0.098 ms/op
Iteration   1: 1.877 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.877 ms/op


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
# Warmup Iteration   1: 5.763 ±(99.9%) 0.155 ms/op
Iteration   1: 3.675 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.675 ms/op


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
# Warmup Iteration   1: 3.592 ±(99.9%) 0.095 ms/op
Iteration   1: 2.112 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.423 ms/op
                 createUser·p0.50:   1.839 ms/op
                 createUser·p0.90:   2.589 ms/op
                 createUser·p0.95:   2.948 ms/op
                 createUser·p0.99:   8.569 ms/op
                 createUser·p0.999:  18.285 ms/op
                 createUser·p0.9999: 21.380 ms/op
                 createUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15266
  mean =      2.112 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13258 
    [ 2.500,  5.000) = 1672 
    [ 5.000,  7.500) = 150 
    [ 7.500, 10.000) = 114 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.423 ms/op
     p(50.0000) =      1.839 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.948 ms/op
     p(99.0000) =      8.569 ms/op
     p(99.9000) =     18.285 ms/op
     p(99.9900) =     21.380 ms/op
     p(99.9990) =     21.398 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 2.754 ±(99.9%) 0.064 ms/op
Iteration   1: 1.973 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.604 ms/op
                 existUser·p0.50:   1.825 ms/op
                 existUser·p0.90:   2.339 ms/op
                 existUser·p0.95:   2.576 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  19.642 ms/op
                 existUser·p0.9999: 20.372 ms/op
                 existUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16580
  mean =      1.973 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15615 
    [ 2.500,  5.000) = 779 
    [ 5.000,  7.500) = 117 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      1.825 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      5.210 ms/op
     p(99.9000) =     19.642 ms/op
     p(99.9900) =     20.372 ms/op
     p(99.9990) =     20.480 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


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
# Warmup Iteration   1: 3.641 ±(99.9%) 0.106 ms/op
Iteration   1: 2.218 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.716 ms/op
                 getUser·p0.50:   2.118 ms/op
                 getUser·p0.90:   2.732 ms/op
                 getUser·p0.95:   2.916 ms/op
                 getUser·p0.99:   3.861 ms/op
                 getUser·p0.999:  15.251 ms/op
                 getUser·p0.9999: 16.885 ms/op
                 getUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14538
  mean =      2.218 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 11701 
    [ 2.500,  3.750) = 2590 
    [ 3.750,  5.000) = 56 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.732 ms/op
     p(95.0000) =      2.916 ms/op
     p(99.0000) =      3.861 ms/op
     p(99.9000) =     15.251 ms/op
     p(99.9900) =     16.885 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 4.787 ±(99.9%) 0.159 ms/op
Iteration   1: 3.339 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.976 ms/op
                 listUser·p0.50:   3.310 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.792 ms/op
                 listUser·p0.999:  6.817 ms/op
                 listUser·p0.9999: 7.184 ms/op
                 listUser·p1.00:   7.184 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9611
  mean =      3.339 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 6 
    [1.500, 2.000) = 31 
    [2.000, 2.500) = 740 
    [2.500, 3.000) = 2579 
    [3.000, 3.500) = 2607 
    [3.500, 4.000) = 2390 
    [4.000, 4.500) = 824 
    [4.500, 5.000) = 185 
    [5.000, 5.500) = 121 
    [5.500, 6.000) = 66 
    [6.000, 6.500) = 50 
    [6.500, 7.000) = 9 
    [7.000, 7.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =      6.817 ms/op
     p(99.9900) =      7.184 ms/op
     p(99.9990) =      7.184 ms/op
     p(99.9999) =      7.184 ms/op
    p(100.0000) =      7.184 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.793          ops/ms
ClientSimple.existUser                       thrpt         13.687          ops/ms
ClientSimple.getUser                         thrpt         10.495          ops/ms
ClientSimple.listUser                        thrpt          8.184          ops/ms
ClientSimple.createUser                       avgt          2.205           ms/op
ClientSimple.existUser                        avgt          1.923           ms/op
ClientSimple.getUser                          avgt          1.877           ms/op
ClientSimple.listUser                         avgt          3.675           ms/op
ClientSimple.createUser                     sample  15266   2.112 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.423           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.839           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.589           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.948           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.569           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.285           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.380           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.398           ms/op
ClientSimple.existUser                      sample  16580   1.973 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.604           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.825           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.339           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.576           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.210           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.642           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.372           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.480           ms/op
ClientSimple.getUser                        sample  14538   2.218 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.716           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.118           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.732           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.916           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.861           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.251           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.885           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.974           ms/op
ClientSimple.listUser                       sample   9611   3.339 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.976           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.310           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.112           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.792           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.817           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.184           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.184           ms/op

Benchmark result is saved to 1718518369143.json
