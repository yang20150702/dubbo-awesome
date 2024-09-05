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
# Warmup Iteration   1: 0.784 ops/ms
Iteration   1: 6.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.110 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.572 ops/ms
Iteration   1: 12.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.587 ops/ms


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
# Warmup Iteration   1: 6.197 ops/ms
Iteration   1: 11.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.961 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.843 ops/ms
Iteration   1: 8.519 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.519 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.256 ±(99.9%) 0.083 ms/op
Iteration   1: 2.304 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.304 ms/op


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
# Warmup Iteration   1: 3.530 ±(99.9%) 0.053 ms/op
Iteration   1: 2.275 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.275 ms/op


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
# Warmup Iteration   1: 3.304 ±(99.9%) 0.066 ms/op
Iteration   1: 2.155 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.155 ms/op


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
# Warmup Iteration   1: 5.151 ±(99.9%) 0.105 ms/op
Iteration   1: 3.627 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.627 ms/op


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
# Warmup Iteration   1: 3.696 ±(99.9%) 0.101 ms/op
Iteration   1: 2.174 ±(99.9%) 0.054 ms/op
                 createUser·p0.00:   0.430 ms/op
                 createUser·p0.50:   1.872 ms/op
                 createUser·p0.90:   2.683 ms/op
                 createUser·p0.95:   2.995 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  26.562 ms/op
                 createUser·p0.9999: 30.394 ms/op
                 createUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14696
  mean =      2.174 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12517 
    [ 2.500,  5.000) = 2016 
    [ 5.000,  7.500) = 35 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.430 ms/op
     p(50.0000) =      1.872 ms/op
     p(90.0000) =      2.683 ms/op
     p(95.0000) =      2.995 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     26.562 ms/op
     p(99.9900) =     30.394 ms/op
     p(99.9990) =     30.933 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


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
# Warmup Iteration   1: 3.189 ±(99.9%) 0.095 ms/op
Iteration   1: 2.127 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.642 ms/op
                 existUser·p0.50:   2.085 ms/op
                 existUser·p0.90:   2.597 ms/op
                 existUser·p0.95:   2.851 ms/op
                 existUser·p0.99:   3.630 ms/op
                 existUser·p0.999:  16.445 ms/op
                 existUser·p0.9999: 17.907 ms/op
                 existUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15043
  mean =      2.127 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 213 
    [ 1.250,  2.500) = 12829 
    [ 2.500,  3.750) = 1865 
    [ 3.750,  5.000) = 62 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      2.085 ms/op
     p(90.0000) =      2.597 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =      3.630 ms/op
     p(99.9000) =     16.445 ms/op
     p(99.9900) =     17.907 ms/op
     p(99.9990) =     17.957 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 3.494 ±(99.9%) 0.092 ms/op
Iteration   1: 1.965 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.491 ms/op
                 getUser·p0.50:   1.796 ms/op
                 getUser·p0.90:   2.396 ms/op
                 getUser·p0.95:   2.703 ms/op
                 getUser·p0.99:   3.627 ms/op
                 getUser·p0.999:  17.334 ms/op
                 getUser·p0.9999: 17.433 ms/op
                 getUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16257
  mean =      1.965 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 118 
    [ 1.250,  2.500) = 14869 
    [ 2.500,  3.750) = 1124 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.491 ms/op
     p(50.0000) =      1.796 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.703 ms/op
     p(99.0000) =      3.627 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     17.433 ms/op
     p(99.9990) =     17.433 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


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
# Warmup Iteration   1: 6.756 ±(99.9%) 0.185 ms/op
Iteration   1: 3.741 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.121 ms/op
                 listUser·p0.99:   7.710 ms/op
                 listUser·p0.999:  16.242 ms/op
                 listUser·p0.9999: 16.351 ms/op
                 listUser·p1.00:   16.351 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8557
  mean =      3.741 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 659 
    [ 2.500,  3.750) = 3848 
    [ 3.750,  5.000) = 3551 
    [ 5.000,  6.250) = 392 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.121 ms/op
     p(99.0000) =      7.710 ms/op
     p(99.9000) =     16.242 ms/op
     p(99.9900) =     16.351 ms/op
     p(99.9990) =     16.351 ms/op
     p(99.9999) =     16.351 ms/op
    p(100.0000) =     16.351 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.110          ops/ms
ClientSimple.existUser                       thrpt         12.587          ops/ms
ClientSimple.getUser                         thrpt         11.961          ops/ms
ClientSimple.listUser                        thrpt          8.519          ops/ms
ClientSimple.createUser                       avgt          2.304           ms/op
ClientSimple.existUser                        avgt          2.275           ms/op
ClientSimple.getUser                          avgt          2.155           ms/op
ClientSimple.listUser                         avgt          3.627           ms/op
ClientSimple.createUser                     sample  14696   2.174 ± 0.054   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.430           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.872           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.683           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.995           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.595           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.562           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.394           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.933           ms/op
ClientSimple.existUser                      sample  15043   2.127 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.642           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.085           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.597           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.851           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.630           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.445           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.907           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.957           ms/op
ClientSimple.getUser                        sample  16257   1.965 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.491           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.796           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.396           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.703           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.627           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.334           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.433           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.433           ms/op
ClientSimple.listUser                       sample   8557   3.741 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.128           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.707           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.596           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.121           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.710           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.242           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.351           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.351           ms/op

Benchmark result is saved to 1725516861468.json
