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
# Warmup Iteration   1: 1.906 ops/ms
Iteration   1: 7.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.423 ops/ms


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
# Warmup Iteration   1: 5.884 ops/ms
Iteration   1: 13.266 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.266 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.966 ops/ms
Iteration   1: 12.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.601 ops/ms


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
# Warmup Iteration   1: 4.601 ops/ms
Iteration   1: 8.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.986 ops/ms


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
# Warmup Iteration   1: 4.790 ±(99.9%) 0.092 ms/op
Iteration   1: 2.327 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.327 ms/op


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
# Warmup Iteration   1: 3.132 ±(99.9%) 0.056 ms/op
Iteration   1: 1.974 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.974 ms/op


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
# Warmup Iteration   1: 3.344 ±(99.9%) 0.053 ms/op
Iteration   1: 2.173 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.173 ms/op


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
# Warmup Iteration   1: 4.406 ±(99.9%) 0.085 ms/op
Iteration   1: 3.380 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.380 ms/op


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
# Warmup Iteration   1: 3.416 ±(99.9%) 0.090 ms/op
Iteration   1: 2.003 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.548 ms/op
                 createUser·p0.50:   1.804 ms/op
                 createUser·p0.90:   2.339 ms/op
                 createUser·p0.95:   2.552 ms/op
                 createUser·p0.99:   5.976 ms/op
                 createUser·p0.999:  35.572 ms/op
                 createUser·p0.9999: 36.438 ms/op
                 createUser·p1.00:   36.438 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16053
  mean =      2.003 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15139 
    [ 2.500,  5.000) = 695 
    [ 5.000,  7.500) = 77 
    [ 7.500, 10.000) = 17 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.548 ms/op
     p(50.0000) =      1.804 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.552 ms/op
     p(99.0000) =      5.976 ms/op
     p(99.9000) =     35.572 ms/op
     p(99.9900) =     36.438 ms/op
     p(99.9990) =     36.438 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


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
# Warmup Iteration   1: 2.950 ±(99.9%) 0.066 ms/op
Iteration   1: 1.713 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.451 ms/op
                 existUser·p0.50:   1.626 ms/op
                 existUser·p0.90:   2.046 ms/op
                 existUser·p0.95:   2.232 ms/op
                 existUser·p0.99:   3.297 ms/op
                 existUser·p0.999:  14.991 ms/op
                 existUser·p0.9999: 15.974 ms/op
                 existUser·p1.00:   15.974 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18668
  mean =      1.713 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 440 
    [ 1.250,  2.500) = 17730 
    [ 2.500,  3.750) = 360 
    [ 3.750,  5.000) = 69 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.451 ms/op
     p(50.0000) =      1.626 ms/op
     p(90.0000) =      2.046 ms/op
     p(95.0000) =      2.232 ms/op
     p(99.0000) =      3.297 ms/op
     p(99.9000) =     14.991 ms/op
     p(99.9900) =     15.974 ms/op
     p(99.9990) =     15.974 ms/op
     p(99.9999) =     15.974 ms/op
    p(100.0000) =     15.974 ms/op


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
# Warmup Iteration   1: 3.319 ±(99.9%) 0.095 ms/op
Iteration   1: 2.105 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.816 ms/op
                 getUser·p0.50:   1.999 ms/op
                 getUser·p0.90:   2.494 ms/op
                 getUser·p0.95:   2.720 ms/op
                 getUser·p0.99:   3.896 ms/op
                 getUser·p0.999:  11.154 ms/op
                 getUser·p0.9999: 11.491 ms/op
                 getUser·p1.00:   11.551 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15190
  mean =      2.105 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 13667 
    [ 2.500,  3.750) = 1303 
    [ 3.750,  5.000) = 98 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      1.999 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      3.896 ms/op
     p(99.9000) =     11.154 ms/op
     p(99.9900) =     11.491 ms/op
     p(99.9990) =     11.551 ms/op
     p(99.9999) =     11.551 ms/op
    p(100.0000) =     11.551 ms/op


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
# Warmup Iteration   1: 4.697 ±(99.9%) 0.130 ms/op
Iteration   1: 3.299 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  17.903 ms/op
                 listUser·p0.9999: 18.383 ms/op
                 listUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9549
  mean =      3.299 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 804 
    [ 2.500,  3.750) = 6523 
    [ 3.750,  5.000) = 1854 
    [ 5.000,  6.250) = 245 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     17.903 ms/op
     p(99.9900) =     18.383 ms/op
     p(99.9990) =     18.383 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.423          ops/ms
ClientSimple.existUser                       thrpt         13.266          ops/ms
ClientSimple.getUser                         thrpt         12.601          ops/ms
ClientSimple.listUser                        thrpt          8.986          ops/ms
ClientSimple.createUser                       avgt          2.327           ms/op
ClientSimple.existUser                        avgt          1.974           ms/op
ClientSimple.getUser                          avgt          2.173           ms/op
ClientSimple.listUser                         avgt          3.380           ms/op
ClientSimple.createUser                     sample  16053   2.003 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.548           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.804           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.339           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.552           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.976           ms/op
ClientSimple.createUser:createUser·p0.999   sample         35.572           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         36.438           ms/op
ClientSimple.createUser:createUser·p1.00    sample         36.438           ms/op
ClientSimple.existUser                      sample  18668   1.713 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.451           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.626           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.046           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.232           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.297           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.991           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.974           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.974           ms/op
ClientSimple.getUser                        sample  15190   2.105 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.816           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.999           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.494           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.720           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.896           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.154           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.491           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.551           ms/op
ClientSimple.listUser                       sample   9549   3.299 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.100           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.941           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.174           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.653           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.676           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.903           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.383           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.383           ms/op

Benchmark result is saved to 1724114596739.json
