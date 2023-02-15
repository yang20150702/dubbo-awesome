# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.099 ops/ms
Iteration   1: 2.770 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.770 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 2.848 ops/ms
Iteration   1: 6.426 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.426 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.637 ops/ms
Iteration   1: 4.992 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.992 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.084 ops/ms
Iteration   1: 1.598 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.598 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 19.676 ±(99.9%) 0.272 ms/op
Iteration   1: 8.032 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  8.032 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.233 ±(99.9%) 0.062 ms/op
Iteration   1: 3.710 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.710 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 12.731 ±(99.9%) 0.176 ms/op
Iteration   1: 4.798 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.798 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 27.090 ±(99.9%) 0.609 ms/op
Iteration   1: 15.362 ±(99.9%) 0.068 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.362 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.108 ±(99.9%) 0.426 ms/op
Iteration   1: 6.847 ±(99.9%) 0.087 ms/op
                 createUser·p0.00:   2.630 ms/op
                 createUser·p0.50:   6.423 ms/op
                 createUser·p0.90:   7.299 ms/op
                 createUser·p0.95:   10.404 ms/op
                 createUser·p0.99:   15.892 ms/op
                 createUser·p0.999:  19.038 ms/op
                 createUser·p0.9999: 19.038 ms/op
                 createUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4707
  mean =      6.847 ±(99.9%) 0.087 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 30 
    [ 3.750,  5.000) = 12 
    [ 5.000,  6.250) = 1032 
    [ 6.250,  7.500) = 3291 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.630 ms/op
     p(50.0000) =      6.423 ms/op
     p(90.0000) =      7.299 ms/op
     p(95.0000) =     10.404 ms/op
     p(99.0000) =     15.892 ms/op
     p(99.9000) =     19.038 ms/op
     p(99.9900) =     19.038 ms/op
     p(99.9990) =     19.038 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.117 ±(99.9%) 0.189 ms/op
Iteration   1: 4.010 ±(99.9%) 0.086 ms/op
                 existUser·p0.00:   1.335 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   4.973 ms/op
                 existUser·p0.95:   5.538 ms/op
                 existUser·p0.99:   14.123 ms/op
                 existUser·p0.999:  28.574 ms/op
                 existUser·p0.9999: 28.869 ms/op
                 existUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8030
  mean =      4.010 ±(99.9%) 0.086 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 857 
    [ 2.500,  5.000) = 6440 
    [ 5.000,  7.500) = 538 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =     14.123 ms/op
     p(99.9000) =     28.574 ms/op
     p(99.9900) =     28.869 ms/op
     p(99.9990) =     28.869 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 11.231 ±(99.9%) 0.349 ms/op
Iteration   1: 4.255 ±(99.9%) 0.044 ms/op
                 getUser·p0.00:   1.921 ms/op
                 getUser·p0.50:   4.047 ms/op
                 getUser·p0.90:   5.104 ms/op
                 getUser·p0.95:   5.620 ms/op
                 getUser·p0.99:   9.159 ms/op
                 getUser·p0.999:  13.817 ms/op
                 getUser·p0.9999: 13.926 ms/op
                 getUser·p1.00:   13.926 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7667
  mean =      4.255 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 57 
    [ 2.500,  3.750) = 2474 
    [ 3.750,  5.000) = 4257 
    [ 5.000,  6.250) = 630 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.921 ms/op
     p(50.0000) =      4.047 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      9.159 ms/op
     p(99.9000) =     13.817 ms/op
     p(99.9900) =     13.926 ms/op
     p(99.9990) =     13.926 ms/op
     p(99.9999) =     13.926 ms/op
    p(100.0000) =     13.926 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 27.954 ±(99.9%) 0.830 ms/op
Iteration   1: 14.989 ±(99.9%) 0.374 ms/op
                 listUser·p0.00:   2.490 ms/op
                 listUser·p0.50:   13.746 ms/op
                 listUser·p0.90:   20.110 ms/op
                 listUser·p0.95:   23.801 ms/op
                 listUser·p0.99:   31.466 ms/op
                 listUser·p0.999:  49.873 ms/op
                 listUser·p0.9999: 49.873 ms/op
                 listUser·p1.00:   49.873 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2172
  mean =     14.989 ±(99.9%) 0.374 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 1 
    [ 5.000, 10.000) = 246 
    [10.000, 15.000) = 1060 
    [15.000, 20.000) = 643 
    [20.000, 25.000) = 144 
    [25.000, 30.000) = 42 
    [30.000, 35.000) = 18 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.490 ms/op
     p(50.0000) =     13.746 ms/op
     p(90.0000) =     20.110 ms/op
     p(95.0000) =     23.801 ms/op
     p(99.0000) =     31.466 ms/op
     p(99.9000) =     49.873 ms/op
     p(99.9900) =     49.873 ms/op
     p(99.9990) =     49.873 ms/op
     p(99.9999) =     49.873 ms/op
    p(100.0000) =     49.873 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.770          ops/ms
Client.existUser                       thrpt         6.426          ops/ms
Client.getUser                         thrpt         4.992          ops/ms
Client.listUser                        thrpt         1.598          ops/ms
Client.createUser                       avgt         8.032           ms/op
Client.existUser                        avgt         3.710           ms/op
Client.getUser                          avgt         4.798           ms/op
Client.listUser                         avgt        15.362           ms/op
Client.createUser                     sample  4707   6.847 ± 0.087   ms/op
Client.createUser:createUser·p0.00    sample         2.630           ms/op
Client.createUser:createUser·p0.50    sample         6.423           ms/op
Client.createUser:createUser·p0.90    sample         7.299           ms/op
Client.createUser:createUser·p0.95    sample        10.404           ms/op
Client.createUser:createUser·p0.99    sample        15.892           ms/op
Client.createUser:createUser·p0.999   sample        19.038           ms/op
Client.createUser:createUser·p0.9999  sample        19.038           ms/op
Client.createUser:createUser·p1.00    sample        19.038           ms/op
Client.existUser                      sample  8030   4.010 ± 0.086   ms/op
Client.existUser:existUser·p0.00      sample         1.335           ms/op
Client.existUser:existUser·p0.50      sample         3.416           ms/op
Client.existUser:existUser·p0.90      sample         4.973           ms/op
Client.existUser:existUser·p0.95      sample         5.538           ms/op
Client.existUser:existUser·p0.99      sample        14.123           ms/op
Client.existUser:existUser·p0.999     sample        28.574           ms/op
Client.existUser:existUser·p0.9999    sample        28.869           ms/op
Client.existUser:existUser·p1.00      sample        28.869           ms/op
Client.getUser                        sample  7667   4.255 ± 0.044   ms/op
Client.getUser:getUser·p0.00          sample         1.921           ms/op
Client.getUser:getUser·p0.50          sample         4.047           ms/op
Client.getUser:getUser·p0.90          sample         5.104           ms/op
Client.getUser:getUser·p0.95          sample         5.620           ms/op
Client.getUser:getUser·p0.99          sample         9.159           ms/op
Client.getUser:getUser·p0.999         sample        13.817           ms/op
Client.getUser:getUser·p0.9999        sample        13.926           ms/op
Client.getUser:getUser·p1.00          sample        13.926           ms/op
Client.listUser                       sample  2172  14.989 ± 0.374   ms/op
Client.listUser:listUser·p0.00        sample         2.490           ms/op
Client.listUser:listUser·p0.50        sample        13.746           ms/op
Client.listUser:listUser·p0.90        sample        20.110           ms/op
Client.listUser:listUser·p0.95        sample        23.801           ms/op
Client.listUser:listUser·p0.99        sample        31.466           ms/op
Client.listUser:listUser·p0.999       sample        49.873           ms/op
Client.listUser:listUser·p0.9999      sample        49.873           ms/op
Client.listUser:listUser·p1.00        sample        49.873           ms/op
