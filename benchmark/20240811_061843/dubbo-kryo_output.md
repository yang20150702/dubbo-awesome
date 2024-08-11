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
# Warmup Iteration   1: 1.944 ops/ms
Iteration   1: 6.930 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.930 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.776 ops/ms
Iteration   1: 12.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.862 ops/ms


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
# Warmup Iteration   1: 4.697 ops/ms
Iteration   1: 13.201 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.201 ops/ms


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
# Warmup Iteration   1: 4.816 ops/ms
Iteration   1: 8.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.302 ops/ms


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
# Warmup Iteration   1: 4.134 ±(99.9%) 0.067 ms/op
Iteration   1: 1.995 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.995 ms/op


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
# Warmup Iteration   1: 3.387 ±(99.9%) 0.058 ms/op
Iteration   1: 1.839 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.839 ms/op


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
# Warmup Iteration   1: 3.288 ±(99.9%) 0.074 ms/op
Iteration   1: 2.146 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.146 ms/op


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
# Warmup Iteration   1: 4.157 ±(99.9%) 0.075 ms/op
Iteration   1: 3.706 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.706 ms/op


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
# Warmup Iteration   1: 3.594 ±(99.9%) 0.097 ms/op
Iteration   1: 2.459 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.857 ms/op
                 createUser·p0.50:   2.232 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  19.956 ms/op
                 createUser·p0.9999: 21.004 ms/op
                 createUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12981
  mean =      2.459 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8468 
    [ 2.500,  5.000) = 4303 
    [ 5.000,  7.500) = 161 
    [ 7.500, 10.000) = 17 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      2.232 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     19.956 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     21.004 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 2.916 ±(99.9%) 0.084 ms/op
Iteration   1: 2.040 ±(99.9%) 0.095 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   1.733 ms/op
                 existUser·p0.90:   2.167 ms/op
                 existUser·p0.95:   2.372 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  71.112 ms/op
                 existUser·p0.9999: 95.498 ms/op
                 existUser·p1.00:   95.945 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15673
  mean =      2.040 ±(99.9%) 0.095 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 15551 
    [ 10.000,  20.000) = 38 
    [ 20.000,  30.000) = 40 
    [ 30.000,  40.000) = 7 
    [ 40.000,  50.000) = 7 
    [ 50.000,  60.000) = 9 
    [ 60.000,  70.000) = 5 
    [ 70.000,  80.000) = 6 
    [ 80.000,  90.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      1.733 ms/op
     p(90.0000) =      2.167 ms/op
     p(95.0000) =      2.372 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =     71.112 ms/op
     p(99.9900) =     95.498 ms/op
     p(99.9990) =     95.945 ms/op
     p(99.9999) =     95.945 ms/op
    p(100.0000) =     95.945 ms/op


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
# Warmup Iteration   1: 3.515 ±(99.9%) 0.086 ms/op
Iteration   1: 2.269 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.494 ms/op
                 getUser·p0.50:   2.195 ms/op
                 getUser·p0.90:   2.732 ms/op
                 getUser·p0.95:   2.945 ms/op
                 getUser·p0.99:   5.437 ms/op
                 getUser·p0.999:  14.107 ms/op
                 getUser·p0.9999: 14.772 ms/op
                 getUser·p1.00:   14.778 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14175
  mean =      2.269 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 10804 
    [ 2.500,  3.750) = 3078 
    [ 3.750,  5.000) = 65 
    [ 5.000,  6.250) = 75 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.494 ms/op
     p(50.0000) =      2.195 ms/op
     p(90.0000) =      2.732 ms/op
     p(95.0000) =      2.945 ms/op
     p(99.0000) =      5.437 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     14.772 ms/op
     p(99.9990) =     14.778 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


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
# Warmup Iteration   1: 4.756 ±(99.9%) 0.141 ms/op
Iteration   1: 3.796 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   0.757 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.931 ms/op
                 listUser·p0.99:   5.915 ms/op
                 listUser·p0.999:  15.771 ms/op
                 listUser·p0.9999: 15.876 ms/op
                 listUser·p1.00:   15.876 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8421
  mean =      3.796 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 297 
    [ 2.500,  3.750) = 3409 
    [ 3.750,  5.000) = 4342 
    [ 5.000,  6.250) = 315 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      4.931 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =     15.771 ms/op
     p(99.9900) =     15.876 ms/op
     p(99.9990) =     15.876 ms/op
     p(99.9999) =     15.876 ms/op
    p(100.0000) =     15.876 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.930          ops/ms
ClientSimple.existUser                       thrpt         12.862          ops/ms
ClientSimple.getUser                         thrpt         13.201          ops/ms
ClientSimple.listUser                        thrpt          8.302          ops/ms
ClientSimple.createUser                       avgt          1.995           ms/op
ClientSimple.existUser                        avgt          1.839           ms/op
ClientSimple.getUser                          avgt          2.146           ms/op
ClientSimple.listUser                         avgt          3.706           ms/op
ClientSimple.createUser                     sample  12981   2.459 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.857           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.232           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.899           ms/op
ClientSimple.createUser:createUser·p0.95    sample          4.317           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.833           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.956           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.004           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.004           ms/op
ClientSimple.existUser                      sample  15673   2.040 ± 0.095   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.725           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.733           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.167           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.372           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.547           ms/op
ClientSimple.existUser:existUser·p0.999     sample         71.112           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         95.498           ms/op
ClientSimple.existUser:existUser·p1.00      sample         95.945           ms/op
ClientSimple.getUser                        sample  14175   2.269 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.494           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.195           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.732           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.945           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.437           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.107           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.772           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.778           ms/op
ClientSimple.listUser                       sample   8421   3.796 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.757           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.871           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.620           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.931           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.915           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.771           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.876           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.876           ms/op

Benchmark result is saved to 1723356848407.json
