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
# Warmup Iteration   1: 1.599 ops/ms
Iteration   1: 7.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.222 ops/ms


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
# Warmup Iteration   1: 5.707 ops/ms
Iteration   1: 12.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.755 ops/ms


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
# Warmup Iteration   1: 5.939 ops/ms
Iteration   1: 11.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.969 ops/ms


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
# Warmup Iteration   1: 5.248 ops/ms
Iteration   1: 7.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.972 ops/ms


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
# Warmup Iteration   1: 4.153 ±(99.9%) 0.079 ms/op
Iteration   1: 2.288 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.288 ms/op


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
# Warmup Iteration   1: 3.312 ±(99.9%) 0.083 ms/op
Iteration   1: 2.134 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.134 ms/op


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
# Warmup Iteration   1: 3.287 ±(99.9%) 0.052 ms/op
Iteration   1: 2.084 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.084 ms/op


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
# Warmup Iteration   1: 4.262 ±(99.9%) 0.074 ms/op
Iteration   1: 3.420 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.420 ms/op


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
# Warmup Iteration   1: 3.858 ±(99.9%) 0.105 ms/op
Iteration   1: 2.059 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   1.855 ms/op
                 createUser·p0.90:   2.388 ms/op
                 createUser·p0.95:   2.673 ms/op
                 createUser·p0.99:   5.525 ms/op
                 createUser·p0.999:  19.562 ms/op
                 createUser·p0.9999: 20.286 ms/op
                 createUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15528
  mean =      2.059 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14392 
    [ 2.500,  5.000) = 956 
    [ 5.000,  7.500) = 51 
    [ 7.500, 10.000) = 48 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      1.855 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.673 ms/op
     p(99.0000) =      5.525 ms/op
     p(99.9000) =     19.562 ms/op
     p(99.9900) =     20.286 ms/op
     p(99.9990) =     20.775 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 3.099 ±(99.9%) 0.085 ms/op
Iteration   1: 2.077 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.568 ms/op
                 existUser·p0.50:   2.001 ms/op
                 existUser·p0.90:   2.687 ms/op
                 existUser·p0.95:   2.912 ms/op
                 existUser·p0.99:   3.589 ms/op
                 existUser·p0.999:  11.583 ms/op
                 existUser·p0.9999: 11.825 ms/op
                 existUser·p1.00:   11.960 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15487
  mean =      2.077 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 200 
    [ 1.250,  2.500) = 12567 
    [ 2.500,  3.750) = 2586 
    [ 3.750,  5.000) = 37 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      2.001 ms/op
     p(90.0000) =      2.687 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      3.589 ms/op
     p(99.9000) =     11.583 ms/op
     p(99.9900) =     11.825 ms/op
     p(99.9990) =     11.960 ms/op
     p(99.9999) =     11.960 ms/op
    p(100.0000) =     11.960 ms/op


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
# Warmup Iteration   1: 3.662 ±(99.9%) 0.110 ms/op
Iteration   1: 2.157 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.856 ms/op
                 getUser·p0.50:   2.081 ms/op
                 getUser·p0.90:   2.613 ms/op
                 getUser·p0.95:   2.736 ms/op
                 getUser·p0.99:   3.653 ms/op
                 getUser·p0.999:  14.189 ms/op
                 getUser·p0.9999: 14.942 ms/op
                 getUser·p1.00:   15.057 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15002
  mean =      2.157 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 12454 
    [ 2.500,  3.750) = 2348 
    [ 3.750,  5.000) = 42 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      2.081 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      2.736 ms/op
     p(99.0000) =      3.653 ms/op
     p(99.9000) =     14.189 ms/op
     p(99.9900) =     14.942 ms/op
     p(99.9990) =     15.057 ms/op
     p(99.9999) =     15.057 ms/op
    p(100.0000) =     15.057 ms/op


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
# Warmup Iteration   1: 4.679 ±(99.9%) 0.130 ms/op
Iteration   1: 3.428 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   1.120 ms/op
                 listUser·p0.50:   3.375 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.829 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  15.811 ms/op
                 listUser·p0.9999: 16.024 ms/op
                 listUser·p1.00:   16.024 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9309
  mean =      3.428 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 1332 
    [ 2.500,  3.750) = 5552 
    [ 3.750,  5.000) = 2011 
    [ 5.000,  6.250) = 232 
    [ 6.250,  7.500) = 111 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.829 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     15.811 ms/op
     p(99.9900) =     16.024 ms/op
     p(99.9990) =     16.024 ms/op
     p(99.9999) =     16.024 ms/op
    p(100.0000) =     16.024 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.222          ops/ms
ClientSimple.existUser                       thrpt         12.755          ops/ms
ClientSimple.getUser                         thrpt         11.969          ops/ms
ClientSimple.listUser                        thrpt          7.972          ops/ms
ClientSimple.createUser                       avgt          2.288           ms/op
ClientSimple.existUser                        avgt          2.134           ms/op
ClientSimple.getUser                          avgt          2.084           ms/op
ClientSimple.listUser                         avgt          3.420           ms/op
ClientSimple.createUser                     sample  15528   2.059 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.938           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.855           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.388           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.673           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.525           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.562           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.286           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.775           ms/op
ClientSimple.existUser                      sample  15487   2.077 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.568           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.001           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.687           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.912           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.589           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.583           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.825           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.960           ms/op
ClientSimple.getUser                        sample  15002   2.157 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.856           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.081           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.613           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.736           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.653           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.189           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.942           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.057           ms/op
ClientSimple.listUser                       sample   9309   3.428 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.120           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.375           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.829           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.152           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.811           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.024           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.024           ms/op

Benchmark result is saved to 1721868153334.json
