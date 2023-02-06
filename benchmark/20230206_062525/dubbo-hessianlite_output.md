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
# Warmup Iteration   1: 1.135 ops/ms
Iteration   1: 2.406 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.406 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 2.675 ops/ms
Iteration   1: 6.647 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.647 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.954 ops/ms
Iteration   1: 5.115 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.115 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 0.796 ops/ms
Iteration   1: 1.210 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.210 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 20.386 ±(99.9%) 0.360 ms/op
Iteration   1: 10.912 ±(99.9%) 0.087 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  10.912 ms/op


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
# Warmup Iteration   1: 9.034 ±(99.9%) 0.113 ms/op
Iteration   1: 4.526 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.526 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.060 ±(99.9%) 0.176 ms/op
Iteration   1: 5.094 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.094 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 29.385 ±(99.9%) 0.450 ms/op
Iteration   1: 20.148 ±(99.9%) 0.130 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  20.148 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 14.646 ±(99.9%) 0.383 ms/op
Iteration   1: 7.639 ±(99.9%) 0.097 ms/op
                 createUser·p0.00:   2.634 ms/op
                 createUser·p0.50:   7.258 ms/op
                 createUser·p0.90:   8.266 ms/op
                 createUser·p0.95:   10.142 ms/op
                 createUser·p0.99:   19.076 ms/op
                 createUser·p0.999:  20.480 ms/op
                 createUser·p0.9999: 20.546 ms/op
                 createUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4191
  mean =      7.639 ±(99.9%) 0.097 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 14 
    [ 5.000,  7.500) = 2673 
    [ 7.500, 10.000) = 1287 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.634 ms/op
     p(50.0000) =      7.258 ms/op
     p(90.0000) =      8.266 ms/op
     p(95.0000) =     10.142 ms/op
     p(99.0000) =     19.076 ms/op
     p(99.9000) =     20.480 ms/op
     p(99.9900) =     20.546 ms/op
     p(99.9990) =     20.546 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


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
# Warmup Iteration   1: 7.930 ±(99.9%) 0.221 ms/op
Iteration   1: 4.738 ±(99.9%) 0.052 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   4.588 ms/op
                 existUser·p0.90:   5.046 ms/op
                 existUser·p0.95:   5.333 ms/op
                 existUser·p0.99:   13.419 ms/op
                 existUser·p0.999:  14.189 ms/op
                 existUser·p0.9999: 14.320 ms/op
                 existUser·p1.00:   14.320 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 6764
  mean =      4.738 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 19 
    [ 2.500,  3.750) = 407 
    [ 3.750,  5.000) = 5431 
    [ 5.000,  6.250) = 654 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.499 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =     13.419 ms/op
     p(99.9000) =     14.189 ms/op
     p(99.9900) =     14.320 ms/op
     p(99.9990) =     14.320 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 10.932 ±(99.9%) 0.422 ms/op
Iteration   1: 5.027 ±(99.9%) 0.099 ms/op
                 getUser·p0.00:   2.175 ms/op
                 getUser·p0.50:   4.628 ms/op
                 getUser·p0.90:   5.685 ms/op
                 getUser·p0.95:   7.487 ms/op
                 getUser·p0.99:   16.335 ms/op
                 getUser·p0.999:  35.783 ms/op
                 getUser·p0.9999: 36.045 ms/op
                 getUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6327
  mean =      5.027 ±(99.9%) 0.099 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 4985 
    [ 5.000,  7.500) = 1019 
    [ 7.500, 10.000) = 136 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      2.175 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      5.685 ms/op
     p(95.0000) =      7.487 ms/op
     p(99.0000) =     16.335 ms/op
     p(99.9000) =     35.783 ms/op
     p(99.9900) =     36.045 ms/op
     p(99.9990) =     36.045 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


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
# Warmup Iteration   1: 29.670 ±(99.9%) 1.082 ms/op
Iteration   1: 18.856 ±(99.9%) 0.355 ms/op
                 listUser·p0.00:   7.422 ms/op
                 listUser·p0.50:   19.366 ms/op
                 listUser·p0.90:   23.908 ms/op
                 listUser·p0.95:   25.264 ms/op
                 listUser·p0.99:   30.736 ms/op
                 listUser·p0.999:  35.697 ms/op
                 listUser·p0.9999: 36.504 ms/op
                 listUser·p1.00:   36.504 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1683
  mean =     18.856 ±(99.9%) 0.355 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 21 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 218 
    [17.500, 20.000) = 512 
    [20.000, 22.500) = 289 
    [22.500, 25.000) = 247 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      7.422 ms/op
     p(50.0000) =     19.366 ms/op
     p(90.0000) =     23.908 ms/op
     p(95.0000) =     25.264 ms/op
     p(99.0000) =     30.736 ms/op
     p(99.9000) =     35.697 ms/op
     p(99.9900) =     36.504 ms/op
     p(99.9990) =     36.504 ms/op
     p(99.9999) =     36.504 ms/op
    p(100.0000) =     36.504 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.406          ops/ms
Client.existUser                       thrpt         6.647          ops/ms
Client.getUser                         thrpt         5.115          ops/ms
Client.listUser                        thrpt         1.210          ops/ms
Client.createUser                       avgt        10.912           ms/op
Client.existUser                        avgt         4.526           ms/op
Client.getUser                          avgt         5.094           ms/op
Client.listUser                         avgt        20.148           ms/op
Client.createUser                     sample  4191   7.639 ± 0.097   ms/op
Client.createUser:createUser·p0.00    sample         2.634           ms/op
Client.createUser:createUser·p0.50    sample         7.258           ms/op
Client.createUser:createUser·p0.90    sample         8.266           ms/op
Client.createUser:createUser·p0.95    sample        10.142           ms/op
Client.createUser:createUser·p0.99    sample        19.076           ms/op
Client.createUser:createUser·p0.999   sample        20.480           ms/op
Client.createUser:createUser·p0.9999  sample        20.546           ms/op
Client.createUser:createUser·p1.00    sample        20.546           ms/op
Client.existUser                      sample  6764   4.738 ± 0.052   ms/op
Client.existUser:existUser·p0.00      sample         1.499           ms/op
Client.existUser:existUser·p0.50      sample         4.588           ms/op
Client.existUser:existUser·p0.90      sample         5.046           ms/op
Client.existUser:existUser·p0.95      sample         5.333           ms/op
Client.existUser:existUser·p0.99      sample        13.419           ms/op
Client.existUser:existUser·p0.999     sample        14.189           ms/op
Client.existUser:existUser·p0.9999    sample        14.320           ms/op
Client.existUser:existUser·p1.00      sample        14.320           ms/op
Client.getUser                        sample  6327   5.027 ± 0.099   ms/op
Client.getUser:getUser·p0.00          sample         2.175           ms/op
Client.getUser:getUser·p0.50          sample         4.628           ms/op
Client.getUser:getUser·p0.90          sample         5.685           ms/op
Client.getUser:getUser·p0.95          sample         7.487           ms/op
Client.getUser:getUser·p0.99          sample        16.335           ms/op
Client.getUser:getUser·p0.999         sample        35.783           ms/op
Client.getUser:getUser·p0.9999        sample        36.045           ms/op
Client.getUser:getUser·p1.00          sample        36.045           ms/op
Client.listUser                       sample  1683  18.856 ± 0.355   ms/op
Client.listUser:listUser·p0.00        sample         7.422           ms/op
Client.listUser:listUser·p0.50        sample        19.366           ms/op
Client.listUser:listUser·p0.90        sample        23.908           ms/op
Client.listUser:listUser·p0.95        sample        25.264           ms/op
Client.listUser:listUser·p0.99        sample        30.736           ms/op
Client.listUser:listUser·p0.999       sample        35.697           ms/op
Client.listUser:listUser·p0.9999      sample        36.504           ms/op
Client.listUser:listUser·p1.00        sample        36.504           ms/op
