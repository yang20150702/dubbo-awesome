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
# Warmup Iteration   1: 0.863 ops/ms
Iteration   1: 1.840 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.840 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:22
# Fork: 1 of 1
# Warmup Iteration   1: 1.721 ops/ms
Iteration   1: 4.491 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.491 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.811 ops/ms
Iteration   1: 4.027 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.027 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 0.573 ops/ms
Iteration   1: 1.129 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.129 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:58
# Fork: 1 of 1
# Warmup Iteration   1: 25.710 ±(99.9%) 0.995 ms/op
Iteration   1: 13.761 ±(99.9%) 0.093 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  13.761 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:51
# Fork: 1 of 1
# Warmup Iteration   1: 9.686 ±(99.9%) 0.145 ms/op
Iteration   1: 5.457 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.457 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:44
# Fork: 1 of 1
# Warmup Iteration   1: 16.803 ±(99.9%) 0.319 ms/op
Iteration   1: 5.959 ±(99.9%) 0.067 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.959 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:36
# Fork: 1 of 1
# Warmup Iteration   1: 34.422 ±(99.9%) 1.033 ms/op
Iteration   1: 22.940 ±(99.9%) 0.160 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  22.940 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 16.806 ±(99.9%) 0.526 ms/op
Iteration   1: 9.119 ±(99.9%) 0.172 ms/op
                 createUser·p0.00:   2.081 ms/op
                 createUser·p0.50:   8.847 ms/op
                 createUser·p0.90:   11.013 ms/op
                 createUser·p0.95:   15.077 ms/op
                 createUser·p0.99:   22.249 ms/op
                 createUser·p0.999:  28.069 ms/op
                 createUser·p0.9999: 30.540 ms/op
                 createUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 3487
  mean =      9.119 ±(99.9%) 0.172 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 140 
    [ 5.000,  7.500) = 579 
    [ 7.500, 10.000) = 2276 
    [10.000, 12.500) = 199 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.081 ms/op
     p(50.0000) =      8.847 ms/op
     p(90.0000) =     11.013 ms/op
     p(95.0000) =     15.077 ms/op
     p(99.0000) =     22.249 ms/op
     p(99.9000) =     28.069 ms/op
     p(99.9900) =     30.540 ms/op
     p(99.9990) =     30.540 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.251 ±(99.9%) 0.439 ms/op
Iteration   1: 5.852 ±(99.9%) 0.132 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   5.464 ms/op
                 existUser·p0.90:   6.645 ms/op
                 existUser·p0.95:   8.454 ms/op
                 existUser·p0.99:   19.164 ms/op
                 existUser·p0.999:  35.684 ms/op
                 existUser·p0.9999: 35.848 ms/op
                 existUser·p1.00:   35.848 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 5508
  mean =      5.852 ±(99.9%) 0.132 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 119 
    [ 2.500,  5.000) = 1086 
    [ 5.000,  7.500) = 3915 
    [ 7.500, 10.000) = 195 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      5.464 ms/op
     p(90.0000) =      6.645 ms/op
     p(95.0000) =      8.454 ms/op
     p(99.0000) =     19.164 ms/op
     p(99.9000) =     35.684 ms/op
     p(99.9900) =     35.848 ms/op
     p(99.9990) =     35.848 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


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
# Warmup Iteration   1: 12.212 ±(99.9%) 0.446 ms/op
Iteration   1: 5.440 ±(99.9%) 0.103 ms/op
                 getUser·p0.00:   1.288 ms/op
                 getUser·p0.50:   5.014 ms/op
                 getUser·p0.90:   7.029 ms/op
                 getUser·p0.95:   8.159 ms/op
                 getUser·p0.99:   18.283 ms/op
                 getUser·p0.999:  26.041 ms/op
                 getUser·p0.9999: 27.296 ms/op
                 getUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 5967
  mean =      5.440 ±(99.9%) 0.103 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 2899 
    [ 5.000,  7.500) = 2597 
    [ 7.500, 10.000) = 269 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      7.029 ms/op
     p(95.0000) =      8.159 ms/op
     p(99.0000) =     18.283 ms/op
     p(99.9000) =     26.041 ms/op
     p(99.9900) =     27.296 ms/op
     p(99.9990) =     27.296 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 32.206 ±(99.9%) 1.095 ms/op
Iteration   1: 21.596 ±(99.9%) 0.294 ms/op
                 listUser·p0.00:   8.045 ms/op
                 listUser·p0.50:   21.365 ms/op
                 listUser·p0.90:   23.691 ms/op
                 listUser·p0.95:   24.510 ms/op
                 listUser·p0.99:   38.933 ms/op
                 listUser·p0.999:  46.307 ms/op
                 listUser·p0.9999: 49.086 ms/op
                 listUser·p1.00:   49.086 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1498
  mean =     21.596 ±(99.9%) 0.294 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 6 
    [10.000, 15.000) = 28 
    [15.000, 20.000) = 257 
    [20.000, 25.000) = 1146 
    [25.000, 30.000) = 20 
    [30.000, 35.000) = 18 
    [35.000, 40.000) = 12 
    [40.000, 45.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      8.045 ms/op
     p(50.0000) =     21.365 ms/op
     p(90.0000) =     23.691 ms/op
     p(95.0000) =     24.510 ms/op
     p(99.0000) =     38.933 ms/op
     p(99.9000) =     46.307 ms/op
     p(99.9900) =     49.086 ms/op
     p(99.9990) =     49.086 ms/op
     p(99.9999) =     49.086 ms/op
    p(100.0000) =     49.086 ms/op


# Run complete. Total time: 00:01:29

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.840          ops/ms
Client.existUser                       thrpt         4.491          ops/ms
Client.getUser                         thrpt         4.027          ops/ms
Client.listUser                        thrpt         1.129          ops/ms
Client.createUser                       avgt        13.761           ms/op
Client.existUser                        avgt         5.457           ms/op
Client.getUser                          avgt         5.959           ms/op
Client.listUser                         avgt        22.940           ms/op
Client.createUser                     sample  3487   9.119 ± 0.172   ms/op
Client.createUser:createUser·p0.00    sample         2.081           ms/op
Client.createUser:createUser·p0.50    sample         8.847           ms/op
Client.createUser:createUser·p0.90    sample        11.013           ms/op
Client.createUser:createUser·p0.95    sample        15.077           ms/op
Client.createUser:createUser·p0.99    sample        22.249           ms/op
Client.createUser:createUser·p0.999   sample        28.069           ms/op
Client.createUser:createUser·p0.9999  sample        30.540           ms/op
Client.createUser:createUser·p1.00    sample        30.540           ms/op
Client.existUser                      sample  5508   5.852 ± 0.132   ms/op
Client.existUser:existUser·p0.00      sample         1.202           ms/op
Client.existUser:existUser·p0.50      sample         5.464           ms/op
Client.existUser:existUser·p0.90      sample         6.645           ms/op
Client.existUser:existUser·p0.95      sample         8.454           ms/op
Client.existUser:existUser·p0.99      sample        19.164           ms/op
Client.existUser:existUser·p0.999     sample        35.684           ms/op
Client.existUser:existUser·p0.9999    sample        35.848           ms/op
Client.existUser:existUser·p1.00      sample        35.848           ms/op
Client.getUser                        sample  5967   5.440 ± 0.103   ms/op
Client.getUser:getUser·p0.00          sample         1.288           ms/op
Client.getUser:getUser·p0.50          sample         5.014           ms/op
Client.getUser:getUser·p0.90          sample         7.029           ms/op
Client.getUser:getUser·p0.95          sample         8.159           ms/op
Client.getUser:getUser·p0.99          sample        18.283           ms/op
Client.getUser:getUser·p0.999         sample        26.041           ms/op
Client.getUser:getUser·p0.9999        sample        27.296           ms/op
Client.getUser:getUser·p1.00          sample        27.296           ms/op
Client.listUser                       sample  1498  21.596 ± 0.294   ms/op
Client.listUser:listUser·p0.00        sample         8.045           ms/op
Client.listUser:listUser·p0.50        sample        21.365           ms/op
Client.listUser:listUser·p0.90        sample        23.691           ms/op
Client.listUser:listUser·p0.95        sample        24.510           ms/op
Client.listUser:listUser·p0.99        sample        38.933           ms/op
Client.listUser:listUser·p0.999       sample        46.307           ms/op
Client.listUser:listUser·p0.9999      sample        49.086           ms/op
Client.listUser:listUser·p1.00        sample        49.086           ms/op
