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
# Warmup Iteration   1: 1.668 ops/ms
Iteration   1: 6.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.892 ops/ms


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
# Warmup Iteration   1: 5.369 ops/ms
Iteration   1: 11.028 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.028 ops/ms


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
# Warmup Iteration   1: 4.290 ops/ms
Iteration   1: 11.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.890 ops/ms


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
# Warmup Iteration   1: 4.115 ops/ms
Iteration   1: 8.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.641 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.300 ±(99.9%) 0.096 ms/op
Iteration   1: 2.451 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.451 ms/op


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
# Warmup Iteration   1: 3.407 ±(99.9%) 0.050 ms/op
Iteration   1: 1.972 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.972 ms/op


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
# Warmup Iteration   1: 3.462 ±(99.9%) 0.056 ms/op
Iteration   1: 2.137 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.137 ms/op


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
# Warmup Iteration   1: 5.333 ±(99.9%) 0.093 ms/op
Iteration   1: 3.507 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.507 ms/op


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
# Warmup Iteration   1: 3.764 ±(99.9%) 0.084 ms/op
Iteration   1: 2.441 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.450 ms/op
                 createUser·p0.50:   2.187 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.506 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  29.491 ms/op
                 createUser·p0.9999: 30.336 ms/op
                 createUser·p1.00:   30.376 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13084
  mean =      2.441 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8692 
    [ 2.500,  5.000) = 4208 
    [ 5.000,  7.500) = 88 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      2.187 ms/op
     p(90.0000) =      3.154 ms/op
     p(95.0000) =      3.506 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     29.491 ms/op
     p(99.9900) =     30.336 ms/op
     p(99.9990) =     30.376 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


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
# Warmup Iteration   1: 3.278 ±(99.9%) 0.082 ms/op
Iteration   1: 2.247 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.546 ms/op
                 existUser·p0.50:   2.200 ms/op
                 existUser·p0.90:   2.663 ms/op
                 existUser·p0.95:   2.859 ms/op
                 existUser·p0.99:   3.759 ms/op
                 existUser·p0.999:  12.284 ms/op
                 existUser·p0.9999: 13.936 ms/op
                 existUser·p1.00:   13.943 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14227
  mean =      2.247 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 192 
    [ 1.250,  2.500) = 11026 
    [ 2.500,  3.750) = 2866 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      2.200 ms/op
     p(90.0000) =      2.663 ms/op
     p(95.0000) =      2.859 ms/op
     p(99.0000) =      3.759 ms/op
     p(99.9000) =     12.284 ms/op
     p(99.9900) =     13.936 ms/op
     p(99.9990) =     13.943 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


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
# Warmup Iteration   1: 3.296 ±(99.9%) 0.091 ms/op
Iteration   1: 2.042 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.426 ms/op
                 getUser·p0.50:   1.913 ms/op
                 getUser·p0.90:   2.519 ms/op
                 getUser·p0.95:   2.793 ms/op
                 getUser·p0.99:   3.933 ms/op
                 getUser·p0.999:  20.356 ms/op
                 getUser·p0.9999: 20.414 ms/op
                 getUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15769
  mean =      2.042 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14007 
    [ 2.500,  5.000) = 1649 
    [ 5.000,  7.500) = 49 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.426 ms/op
     p(50.0000) =      1.913 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.793 ms/op
     p(99.0000) =      3.933 ms/op
     p(99.9000) =     20.356 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     20.414 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


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
# Warmup Iteration   1: 4.593 ±(99.9%) 0.131 ms/op
Iteration   1: 4.455 ±(99.9%) 0.049 ms/op
                 listUser·p0.00:   0.861 ms/op
                 listUser·p0.50:   4.293 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.900 ms/op
                 listUser·p0.999:  20.351 ms/op
                 listUser·p0.9999: 21.758 ms/op
                 listUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 7176
  mean =      4.455 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 84 
    [ 2.500,  5.000) = 5601 
    [ 5.000,  7.500) = 1456 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.374 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      6.900 ms/op
     p(99.9000) =     20.351 ms/op
     p(99.9900) =     21.758 ms/op
     p(99.9990) =     21.758 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.892          ops/ms
ClientSimple.existUser                       thrpt         11.028          ops/ms
ClientSimple.getUser                         thrpt         11.890          ops/ms
ClientSimple.listUser                        thrpt          8.641          ops/ms
ClientSimple.createUser                       avgt          2.451           ms/op
ClientSimple.existUser                        avgt          1.972           ms/op
ClientSimple.getUser                          avgt          2.137           ms/op
ClientSimple.listUser                         avgt          3.507           ms/op
ClientSimple.createUser                     sample  13084   2.441 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.450           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.187           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.154           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.506           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.431           ms/op
ClientSimple.createUser:createUser·p0.999   sample         29.491           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.336           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.376           ms/op
ClientSimple.existUser                      sample  14227   2.247 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.546           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.200           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.663           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.859           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.759           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.284           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.936           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.943           ms/op
ClientSimple.getUser                        sample  15769   2.042 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.426           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.913           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.519           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.793           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.933           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.356           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.414           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.414           ms/op
ClientSimple.listUser                       sample   7176   4.455 ± 0.049   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.861           ms/op
ClientSimple.listUser:listUser·p0.50        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.90        sample          5.374           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.620           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.900           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.351           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.758           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.758           ms/op

Benchmark result is saved to 1713895845591.json
