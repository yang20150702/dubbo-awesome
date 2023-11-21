# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.243 ops/ms
Iteration   1: 6.109 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.109 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.659 ops/ms
Iteration   1: 14.396 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.396 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.621 ops/ms
Iteration   1: 8.803 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.803 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.308 ops/ms
Iteration   1: 3.324 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.324 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 6.154 ±(99.9%) 0.063 ms/op
Iteration   1: 2.948 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.948 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.925 ±(99.9%) 0.035 ms/op
Iteration   1: 1.854 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.854 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.393 ±(99.9%) 0.046 ms/op
Iteration   1: 2.838 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.838 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.307 ±(99.9%) 0.278 ms/op
Iteration   1: 8.422 ±(99.9%) 0.088 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.422 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.210 ±(99.9%) 0.103 ms/op
Iteration   1: 3.408 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   1.013 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   5.005 ms/op
                 createUser·p0.99:   7.143 ms/op
                 createUser·p0.999:  11.829 ms/op
                 createUser·p0.9999: 12.567 ms/op
                 createUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9575
  mean =      3.408 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 930 
    [ 2.500,  3.750) = 6080 
    [ 3.750,  5.000) = 2080 
    [ 5.000,  6.250) = 246 
    [ 6.250,  7.500) = 200 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.013 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     11.829 ms/op
     p(99.9900) =     12.567 ms/op
     p(99.9990) =     12.567 ms/op
     p(99.9999) =     12.567 ms/op
    p(100.0000) =     12.567 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.872 ±(99.9%) 0.050 ms/op
Iteration   1: 2.070 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.469 ms/op
                 existUser·p0.50:   1.991 ms/op
                 existUser·p0.90:   2.642 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   6.210 ms/op
                 existUser·p0.999:  12.714 ms/op
                 existUser·p0.9999: 13.017 ms/op
                 existUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15344
  mean =      2.070 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1084 
    [ 1.250,  2.500) = 12129 
    [ 2.500,  3.750) = 1775 
    [ 3.750,  5.000) = 166 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.469 ms/op
     p(50.0000) =      1.991 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     12.714 ms/op
     p(99.9900) =     13.017 ms/op
     p(99.9990) =     13.025 ms/op
     p(99.9999) =     13.025 ms/op
    p(100.0000) =     13.025 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.312 ±(99.9%) 0.103 ms/op
Iteration   1: 3.463 ±(99.9%) 0.279 ms/op
                 getUser·p0.00:   0.548 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   6.318 ms/op
                 getUser·p0.999:  140.771 ms/op
                 getUser·p0.9999: 150.209 ms/op
                 getUser·p1.00:   150.209 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9234
  mean =      3.463 ±(99.9%) 0.279 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 9200 
    [ 12.500,  25.000) = 2 
    [ 25.000,  37.500) = 0 
    [ 37.500,  50.000) = 0 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 0 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 31 
    [150.000, 162.500) = 1 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.548 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      6.318 ms/op
     p(99.9000) =    140.771 ms/op
     p(99.9900) =    150.209 ms/op
     p(99.9990) =    150.209 ms/op
     p(99.9999) =    150.209 ms/op
    p(100.0000) =    150.209 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 11.614 ±(99.9%) 0.365 ms/op
Iteration   1: 7.809 ±(99.9%) 0.106 ms/op
                 listUser·p0.00:   2.540 ms/op
                 listUser·p0.50:   7.487 ms/op
                 listUser·p0.90:   10.306 ms/op
                 listUser·p0.95:   11.534 ms/op
                 listUser·p0.99:   15.533 ms/op
                 listUser·p0.999:  17.400 ms/op
                 listUser·p0.9999: 21.103 ms/op
                 listUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4091
  mean =      7.809 ±(99.9%) 0.106 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 179 
    [ 5.000,  7.500) = 1872 
    [ 7.500, 10.000) = 1553 
    [10.000, 12.500) = 380 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.540 ms/op
     p(50.0000) =      7.487 ms/op
     p(90.0000) =     10.306 ms/op
     p(95.0000) =     11.534 ms/op
     p(99.0000) =     15.533 ms/op
     p(99.9000) =     17.400 ms/op
     p(99.9900) =     21.103 ms/op
     p(99.9990) =     21.103 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt    Score   Error   Units
Client.createUser                      thrpt           6.109          ops/ms
Client.existUser                       thrpt          14.396          ops/ms
Client.getUser                         thrpt           8.803          ops/ms
Client.listUser                        thrpt           3.324          ops/ms
Client.createUser                       avgt           2.948           ms/op
Client.existUser                        avgt           1.854           ms/op
Client.getUser                          avgt           2.838           ms/op
Client.listUser                         avgt           8.422           ms/op
Client.createUser                     sample   9575    3.408 ± 0.034   ms/op
Client.createUser:createUser·p0.00    sample           1.013           ms/op
Client.createUser:createUser·p0.50    sample           3.248           ms/op
Client.createUser:createUser·p0.90    sample           4.309           ms/op
Client.createUser:createUser·p0.95    sample           5.005           ms/op
Client.createUser:createUser·p0.99    sample           7.143           ms/op
Client.createUser:createUser·p0.999   sample          11.829           ms/op
Client.createUser:createUser·p0.9999  sample          12.567           ms/op
Client.createUser:createUser·p1.00    sample          12.567           ms/op
Client.existUser                      sample  15344    2.070 ± 0.025   ms/op
Client.existUser:existUser·p0.00      sample           0.469           ms/op
Client.existUser:existUser·p0.50      sample           1.991           ms/op
Client.existUser:existUser·p0.90      sample           2.642           ms/op
Client.existUser:existUser·p0.95      sample           3.068           ms/op
Client.existUser:existUser·p0.99      sample           6.210           ms/op
Client.existUser:existUser·p0.999     sample          12.714           ms/op
Client.existUser:existUser·p0.9999    sample          13.017           ms/op
Client.existUser:existUser·p1.00      sample          13.025           ms/op
Client.getUser                        sample   9234    3.463 ± 0.279   ms/op
Client.getUser:getUser·p0.00          sample           0.548           ms/op
Client.getUser:getUser·p0.50          sample           2.986           ms/op
Client.getUser:getUser·p0.90          sample           3.699           ms/op
Client.getUser:getUser·p0.95          sample           4.030           ms/op
Client.getUser:getUser·p0.99          sample           6.318           ms/op
Client.getUser:getUser·p0.999         sample         140.771           ms/op
Client.getUser:getUser·p0.9999        sample         150.209           ms/op
Client.getUser:getUser·p1.00          sample         150.209           ms/op
Client.listUser                       sample   4091    7.809 ± 0.106   ms/op
Client.listUser:listUser·p0.00        sample           2.540           ms/op
Client.listUser:listUser·p0.50        sample           7.487           ms/op
Client.listUser:listUser·p0.90        sample          10.306           ms/op
Client.listUser:listUser·p0.95        sample          11.534           ms/op
Client.listUser:listUser·p0.99        sample          15.533           ms/op
Client.listUser:listUser·p0.999       sample          17.400           ms/op
Client.listUser:listUser·p0.9999      sample          21.103           ms/op
Client.listUser:listUser·p1.00        sample          21.103           ms/op
