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
# Warmup Iteration   1: 0.684 ops/ms
Iteration   1: 5.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.520 ops/ms


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
# Warmup Iteration   1: 6.318 ops/ms
Iteration   1: 12.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.861 ops/ms


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
# Warmup Iteration   1: 5.611 ops/ms
Iteration   1: 11.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.868 ops/ms


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
# Warmup Iteration   1: 4.415 ops/ms
Iteration   1: 8.202 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.202 ops/ms


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
# Warmup Iteration   1: 4.246 ±(99.9%) 0.088 ms/op
Iteration   1: 2.162 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.162 ms/op


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
# Warmup Iteration   1: 3.265 ±(99.9%) 0.052 ms/op
Iteration   1: 2.150 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.150 ms/op


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
# Warmup Iteration   1: 3.640 ±(99.9%) 0.100 ms/op
Iteration   1: 2.014 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.014 ms/op


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
# Warmup Iteration   1: 4.683 ±(99.9%) 0.090 ms/op
Iteration   1: 3.680 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.680 ms/op


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
# Warmup Iteration   1: 3.500 ±(99.9%) 0.092 ms/op
Iteration   1: 2.358 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.672 ms/op
                 createUser·p0.50:   2.269 ms/op
                 createUser·p0.90:   2.830 ms/op
                 createUser·p0.95:   3.039 ms/op
                 createUser·p0.99:   4.630 ms/op
                 createUser·p0.999:  22.592 ms/op
                 createUser·p0.9999: 27.071 ms/op
                 createUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13588
  mean =      2.358 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9609 
    [ 2.500,  5.000) = 3859 
    [ 5.000,  7.500) = 63 
    [ 7.500, 10.000) = 24 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      2.269 ms/op
     p(90.0000) =      2.830 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      4.630 ms/op
     p(99.9000) =     22.592 ms/op
     p(99.9900) =     27.071 ms/op
     p(99.9990) =     27.165 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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
# Warmup Iteration   1: 3.275 ±(99.9%) 0.081 ms/op
Iteration   1: 2.150 ±(99.9%) 0.036 ms/op
                 existUser·p0.00:   0.563 ms/op
                 existUser·p0.50:   2.042 ms/op
                 existUser·p0.90:   2.720 ms/op
                 existUser·p0.95:   2.941 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  26.444 ms/op
                 existUser·p0.9999: 26.984 ms/op
                 existUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14999
  mean =      2.150 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12315 
    [ 2.500,  5.000) = 2522 
    [ 5.000,  7.500) = 92 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      2.042 ms/op
     p(90.0000) =      2.720 ms/op
     p(95.0000) =      2.941 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     26.444 ms/op
     p(99.9900) =     26.984 ms/op
     p(99.9990) =     27.001 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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
# Warmup Iteration   1: 3.406 ±(99.9%) 0.084 ms/op
Iteration   1: 2.139 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.530 ms/op
                 getUser·p0.50:   1.831 ms/op
                 getUser·p0.90:   3.170 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  11.568 ms/op
                 getUser·p0.9999: 12.305 ms/op
                 getUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14932
  mean =      2.139 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 11678 
    [ 2.500,  3.750) = 2540 
    [ 3.750,  5.000) = 590 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      1.831 ms/op
     p(90.0000) =      3.170 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =     11.568 ms/op
     p(99.9900) =     12.305 ms/op
     p(99.9990) =     12.321 ms/op
     p(99.9999) =     12.321 ms/op
    p(100.0000) =     12.321 ms/op


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
# Warmup Iteration   1: 5.074 ±(99.9%) 0.206 ms/op
Iteration   1: 3.618 ±(99.9%) 0.065 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   3.305 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.569 ms/op
                 listUser·p0.99:   7.916 ms/op
                 listUser·p0.999:  29.264 ms/op
                 listUser·p0.9999: 29.393 ms/op
                 listUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8942
  mean =      3.618 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 659 
    [ 2.500,  5.000) = 7496 
    [ 5.000,  7.500) = 668 
    [ 7.500, 10.000) = 85 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.569 ms/op
     p(99.0000) =      7.916 ms/op
     p(99.9000) =     29.264 ms/op
     p(99.9900) =     29.393 ms/op
     p(99.9990) =     29.393 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.520          ops/ms
ClientSimple.existUser                       thrpt         12.861          ops/ms
ClientSimple.getUser                         thrpt         11.868          ops/ms
ClientSimple.listUser                        thrpt          8.202          ops/ms
ClientSimple.createUser                       avgt          2.162           ms/op
ClientSimple.existUser                        avgt          2.150           ms/op
ClientSimple.getUser                          avgt          2.014           ms/op
ClientSimple.listUser                         avgt          3.680           ms/op
ClientSimple.createUser                     sample  13588   2.358 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.672           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.269           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.830           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.039           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.630           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.592           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.071           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.165           ms/op
ClientSimple.existUser                      sample  14999   2.150 ± 0.036   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.563           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.042           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.720           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.941           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.562           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.444           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.984           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.001           ms/op
ClientSimple.getUser                        sample  14932   2.139 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.530           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.831           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.170           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.645           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.211           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.568           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.305           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.321           ms/op
ClientSimple.listUser                       sample   8942   3.618 ± 0.065   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.225           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.305           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.907           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.569           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.916           ms/op
ClientSimple.listUser:listUser·p0.999       sample         29.264           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         29.393           ms/op
ClientSimple.listUser:listUser·p1.00        sample         29.393           ms/op

Benchmark result is saved to 1724847531307.json
