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
# Warmup Iteration   1: 1.624 ops/ms
Iteration   1: 5.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.956 ops/ms


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
# Warmup Iteration   1: 5.038 ops/ms
Iteration   1: 9.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  9.554 ops/ms


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
# Warmup Iteration   1: 5.457 ops/ms
Iteration   1: 10.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.986 ops/ms


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
# Warmup Iteration   1: 4.669 ops/ms
Iteration   1: 9.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.039 ops/ms


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
# Warmup Iteration   1: 3.985 ±(99.9%) 0.064 ms/op
Iteration   1: 2.141 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.141 ms/op


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
# Warmup Iteration   1: 3.432 ±(99.9%) 0.064 ms/op
Iteration   1: 1.916 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.916 ms/op


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
# Warmup Iteration   1: 3.272 ±(99.9%) 0.058 ms/op
Iteration   1: 2.019 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.019 ms/op


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
# Warmup Iteration   1: 5.035 ±(99.9%) 0.118 ms/op
Iteration   1: 3.403 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.403 ms/op


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
# Warmup Iteration   1: 3.626 ±(99.9%) 0.113 ms/op
Iteration   1: 2.312 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.412 ms/op
                 createUser·p0.50:   2.118 ms/op
                 createUser·p0.90:   2.896 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   6.322 ms/op
                 createUser·p0.999:  18.388 ms/op
                 createUser·p0.9999: 19.712 ms/op
                 createUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13831
  mean =      2.312 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 372 
    [ 1.250,  2.500) = 9918 
    [ 2.500,  3.750) = 3132 
    [ 3.750,  5.000) = 127 
    [ 5.000,  6.250) = 131 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.412 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.896 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      6.322 ms/op
     p(99.9000) =     18.388 ms/op
     p(99.9900) =     19.712 ms/op
     p(99.9990) =     19.825 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 3.283 ±(99.9%) 0.090 ms/op
Iteration   1: 2.024 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.644 ms/op
                 existUser·p0.50:   1.849 ms/op
                 existUser·p0.90:   2.511 ms/op
                 existUser·p0.95:   2.703 ms/op
                 existUser·p0.99:   5.362 ms/op
                 existUser·p0.999:  21.266 ms/op
                 existUser·p0.9999: 22.150 ms/op
                 existUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15786
  mean =      2.024 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14131 
    [ 2.500,  5.000) = 1462 
    [ 5.000,  7.500) = 94 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      1.849 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.703 ms/op
     p(99.0000) =      5.362 ms/op
     p(99.9000) =     21.266 ms/op
     p(99.9900) =     22.150 ms/op
     p(99.9990) =     22.282 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


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
# Warmup Iteration   1: 3.535 ±(99.9%) 0.111 ms/op
Iteration   1: 2.167 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.489 ms/op
                 getUser·p0.50:   1.980 ms/op
                 getUser·p0.90:   2.847 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  15.438 ms/op
                 getUser·p0.9999: 22.153 ms/op
                 getUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14736
  mean =      2.167 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11996 
    [ 2.500,  5.000) = 2567 
    [ 5.000,  7.500) = 73 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.489 ms/op
     p(50.0000) =      1.980 ms/op
     p(90.0000) =      2.847 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     15.438 ms/op
     p(99.9900) =     22.153 ms/op
     p(99.9990) =     22.479 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


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
# Warmup Iteration   1: 4.527 ±(99.9%) 0.135 ms/op
Iteration   1: 3.781 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  17.930 ms/op
                 listUser·p0.9999: 18.285 ms/op
                 listUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8452
  mean =      3.781 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 605 
    [ 2.500,  3.750) = 3811 
    [ 3.750,  5.000) = 3582 
    [ 5.000,  6.250) = 285 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     17.930 ms/op
     p(99.9900) =     18.285 ms/op
     p(99.9990) =     18.285 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.956          ops/ms
ClientSimple.existUser                       thrpt          9.554          ops/ms
ClientSimple.getUser                         thrpt         10.986          ops/ms
ClientSimple.listUser                        thrpt          9.039          ops/ms
ClientSimple.createUser                       avgt          2.141           ms/op
ClientSimple.existUser                        avgt          1.916           ms/op
ClientSimple.getUser                          avgt          2.019           ms/op
ClientSimple.listUser                         avgt          3.403           ms/op
ClientSimple.createUser                     sample  13831   2.312 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.412           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.118           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.896           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.199           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.322           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.388           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.712           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.825           ms/op
ClientSimple.existUser                      sample  15786   2.024 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.644           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.849           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.511           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.703           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.362           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.266           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.150           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.282           ms/op
ClientSimple.getUser                        sample  14736   2.167 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.489           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.980           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.847           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.133           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.595           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.438           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.153           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.479           ms/op
ClientSimple.listUser                       sample   8452   3.781 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.135           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.711           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.686           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.046           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.569           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.930           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.285           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.285           ms/op

Benchmark result is saved to 1720527508706.json
