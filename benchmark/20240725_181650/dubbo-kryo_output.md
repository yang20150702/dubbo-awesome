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
# Warmup Iteration   1: 1.769 ops/ms
Iteration   1: 7.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.706 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.615 ops/ms
Iteration   1: 13.271 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.271 ops/ms


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
# Warmup Iteration   1: 5.402 ops/ms
Iteration   1: 12.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.240 ops/ms


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
# Warmup Iteration   1: 5.679 ops/ms
Iteration   1: 8.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.220 ops/ms


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
# Warmup Iteration   1: 4.149 ±(99.9%) 0.085 ms/op
Iteration   1: 2.358 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.358 ms/op


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
# Warmup Iteration   1: 3.342 ±(99.9%) 0.053 ms/op
Iteration   1: 2.177 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.177 ms/op


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
# Warmup Iteration   1: 3.200 ±(99.9%) 0.055 ms/op
Iteration   1: 2.047 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.047 ms/op


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
# Warmup Iteration   1: 4.223 ±(99.9%) 0.092 ms/op
Iteration   1: 3.431 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.431 ms/op


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
# Warmup Iteration   1: 3.597 ±(99.9%) 0.099 ms/op
Iteration   1: 2.142 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.453 ms/op
                 createUser·p0.50:   1.958 ms/op
                 createUser·p0.90:   2.765 ms/op
                 createUser·p0.95:   3.019 ms/op
                 createUser·p0.99:   6.398 ms/op
                 createUser·p0.999:  23.333 ms/op
                 createUser·p0.9999: 27.378 ms/op
                 createUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14934
  mean =      2.142 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12019 
    [ 2.500,  5.000) = 2650 
    [ 5.000,  7.500) = 165 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.453 ms/op
     p(50.0000) =      1.958 ms/op
     p(90.0000) =      2.765 ms/op
     p(95.0000) =      3.019 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     23.333 ms/op
     p(99.9900) =     27.378 ms/op
     p(99.9990) =     27.394 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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
# Warmup Iteration   1: 3.035 ±(99.9%) 0.085 ms/op
Iteration   1: 2.073 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   1.960 ms/op
                 existUser·p0.90:   2.666 ms/op
                 existUser·p0.95:   2.970 ms/op
                 existUser·p0.99:   4.024 ms/op
                 existUser·p0.999:  14.254 ms/op
                 existUser·p0.9999: 14.538 ms/op
                 existUser·p1.00:   14.877 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15589
  mean =      2.073 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 275 
    [ 1.250,  2.500) = 12965 
    [ 2.500,  3.750) = 2115 
    [ 3.750,  5.000) = 166 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      1.960 ms/op
     p(90.0000) =      2.666 ms/op
     p(95.0000) =      2.970 ms/op
     p(99.0000) =      4.024 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     14.538 ms/op
     p(99.9990) =     14.877 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


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
# Warmup Iteration   1: 3.467 ±(99.9%) 0.078 ms/op
Iteration   1: 2.037 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.681 ms/op
                 getUser·p0.50:   1.851 ms/op
                 getUser·p0.90:   2.789 ms/op
                 getUser·p0.95:   3.018 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  14.485 ms/op
                 getUser·p0.9999: 19.067 ms/op
                 getUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15704
  mean =      2.037 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 614 
    [ 1.250,  2.500) = 11863 
    [ 2.500,  3.750) = 2985 
    [ 3.750,  5.000) = 100 
    [ 5.000,  6.250) = 103 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      1.851 ms/op
     p(90.0000) =      2.789 ms/op
     p(95.0000) =      3.018 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =     14.485 ms/op
     p(99.9900) =     19.067 ms/op
     p(99.9990) =     19.497 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 5.550 ±(99.9%) 0.193 ms/op
Iteration   1: 3.631 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.735 ms/op
                 listUser·p0.50:   3.535 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   5.153 ms/op
                 listUser·p0.99:   8.529 ms/op
                 listUser·p0.999:  17.668 ms/op
                 listUser·p0.9999: 19.005 ms/op
                 listUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8801
  mean =      3.631 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 16 
    [ 1.250,  2.500) = 530 
    [ 2.500,  3.750) = 5078 
    [ 3.750,  5.000) = 2678 
    [ 5.000,  6.250) = 307 
    [ 6.250,  7.500) = 88 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      5.153 ms/op
     p(99.0000) =      8.529 ms/op
     p(99.9000) =     17.668 ms/op
     p(99.9900) =     19.005 ms/op
     p(99.9990) =     19.005 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.706          ops/ms
ClientSimple.existUser                       thrpt         13.271          ops/ms
ClientSimple.getUser                         thrpt         12.240          ops/ms
ClientSimple.listUser                        thrpt          8.220          ops/ms
ClientSimple.createUser                       avgt          2.358           ms/op
ClientSimple.existUser                        avgt          2.177           ms/op
ClientSimple.getUser                          avgt          2.047           ms/op
ClientSimple.listUser                         avgt          3.431           ms/op
ClientSimple.createUser                     sample  14934   2.142 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.453           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.958           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.765           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.019           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.398           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.333           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.378           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.394           ms/op
ClientSimple.existUser                      sample  15589   2.073 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.732           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.960           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.666           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.970           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.024           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.254           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.538           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.877           ms/op
ClientSimple.getUser                        sample  15704   2.037 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.681           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.851           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.789           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.018           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.702           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.485           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.067           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.497           ms/op
ClientSimple.listUser                       sample   8801   3.631 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.735           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.535           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.153           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.529           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.668           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.005           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.005           ms/op

Benchmark result is saved to 1721931151279.json
