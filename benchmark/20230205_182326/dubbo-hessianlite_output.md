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
# Warmup Iteration   1: 0.769 ops/ms
Iteration   1: 1.913 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.913 ops/ms


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
# Warmup Iteration   1: 2.665 ops/ms
Iteration   1: 7.603 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.603 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.939 ops/ms
Iteration   1: 3.680 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.680 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 0.705 ops/ms
Iteration   1: 0.980 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.980 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:59
# Fork: 1 of 1
# Warmup Iteration   1: 22.943 ±(99.9%) 0.519 ms/op
Iteration   1: 11.369 ±(99.9%) 0.050 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  11.369 ms/op


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
# Warmup Iteration   1: 10.785 ±(99.9%) 0.125 ms/op
Iteration   1: 6.277 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.277 ms/op


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
# Warmup Iteration   1: 10.101 ±(99.9%) 0.132 ms/op
Iteration   1: 5.732 ±(99.9%) 0.058 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.732 ms/op


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
# Warmup Iteration   1: 35.403 ±(99.9%) 0.917 ms/op
Iteration   1: 22.213 ±(99.9%) 0.189 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  22.213 ms/op


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
# Warmup Iteration   1: 16.094 ±(99.9%) 0.580 ms/op
Iteration   1: 6.915 ±(99.9%) 0.188 ms/op
                 createUser·p0.00:   2.130 ms/op
                 createUser·p0.50:   6.988 ms/op
                 createUser·p0.90:   9.830 ms/op
                 createUser·p0.95:   15.116 ms/op
                 createUser·p0.99:   22.751 ms/op
                 createUser·p0.999:  25.592 ms/op
                 createUser·p0.9999: 25.657 ms/op
                 createUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4583
  mean =      6.915 ±(99.9%) 0.188 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 1636 
    [ 5.000,  7.500) = 1248 
    [ 7.500, 10.000) = 1263 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      2.130 ms/op
     p(50.0000) =      6.988 ms/op
     p(90.0000) =      9.830 ms/op
     p(95.0000) =     15.116 ms/op
     p(99.0000) =     22.751 ms/op
     p(99.9000) =     25.592 ms/op
     p(99.9900) =     25.657 ms/op
     p(99.9990) =     25.657 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 9.899 ±(99.9%) 0.310 ms/op
Iteration   1: 5.042 ±(99.9%) 0.109 ms/op
                 existUser·p0.00:   1.280 ms/op
                 existUser·p0.50:   4.669 ms/op
                 existUser·p0.90:   5.554 ms/op
                 existUser·p0.95:   6.930 ms/op
                 existUser·p0.99:   15.705 ms/op
                 existUser·p0.999:  35.301 ms/op
                 existUser·p0.9999: 35.652 ms/op
                 existUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 6344
  mean =      5.042 ±(99.9%) 0.109 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 4170 
    [ 5.000,  7.500) = 1887 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      5.554 ms/op
     p(95.0000) =      6.930 ms/op
     p(99.0000) =     15.705 ms/op
     p(99.9000) =     35.301 ms/op
     p(99.9900) =     35.652 ms/op
     p(99.9990) =     35.652 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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
# Warmup Iteration   1: 16.179 ±(99.9%) 0.469 ms/op
Iteration   1: 6.319 ±(99.9%) 0.144 ms/op
                 getUser·p0.00:   1.898 ms/op
                 getUser·p0.50:   5.792 ms/op
                 getUser·p0.90:   7.930 ms/op
                 getUser·p0.95:   9.044 ms/op
                 getUser·p0.99:   19.104 ms/op
                 getUser·p0.999:  37.148 ms/op
                 getUser·p0.9999: 38.339 ms/op
                 getUser·p1.00:   38.339 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 5171
  mean =      6.319 ±(99.9%) 0.144 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 1110 
    [ 5.000,  7.500) = 3268 
    [ 7.500, 10.000) = 559 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.898 ms/op
     p(50.0000) =      5.792 ms/op
     p(90.0000) =      7.930 ms/op
     p(95.0000) =      9.044 ms/op
     p(99.0000) =     19.104 ms/op
     p(99.9000) =     37.148 ms/op
     p(99.9900) =     38.339 ms/op
     p(99.9990) =     38.339 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


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
# Warmup Iteration   1: 31.356 ±(99.9%) 1.309 ms/op
Iteration   1: 23.625 ±(99.9%) 0.405 ms/op
                 listUser·p0.00:   5.988 ms/op
                 listUser·p0.50:   22.118 ms/op
                 listUser·p0.90:   30.474 ms/op
                 listUser·p0.95:   33.948 ms/op
                 listUser·p0.99:   40.370 ms/op
                 listUser·p0.999:  42.205 ms/op
                 listUser·p0.9999: 42.402 ms/op
                 listUser·p1.00:   42.402 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1374
  mean =     23.625 ±(99.9%) 0.405 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 2 
    [10.000, 15.000) = 8 
    [15.000, 20.000) = 73 
    [20.000, 25.000) = 992 
    [25.000, 30.000) = 147 
    [30.000, 35.000) = 101 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 20 

  Percentiles, ms/op:
      p(0.0000) =      5.988 ms/op
     p(50.0000) =     22.118 ms/op
     p(90.0000) =     30.474 ms/op
     p(95.0000) =     33.948 ms/op
     p(99.0000) =     40.370 ms/op
     p(99.9000) =     42.205 ms/op
     p(99.9900) =     42.402 ms/op
     p(99.9990) =     42.402 ms/op
     p(99.9999) =     42.402 ms/op
    p(100.0000) =     42.402 ms/op


# Run complete. Total time: 00:01:29

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.913          ops/ms
Client.existUser                       thrpt         7.603          ops/ms
Client.getUser                         thrpt         3.680          ops/ms
Client.listUser                        thrpt         0.980          ops/ms
Client.createUser                       avgt        11.369           ms/op
Client.existUser                        avgt         6.277           ms/op
Client.getUser                          avgt         5.732           ms/op
Client.listUser                         avgt        22.213           ms/op
Client.createUser                     sample  4583   6.915 ± 0.188   ms/op
Client.createUser:createUser·p0.00    sample         2.130           ms/op
Client.createUser:createUser·p0.50    sample         6.988           ms/op
Client.createUser:createUser·p0.90    sample         9.830           ms/op
Client.createUser:createUser·p0.95    sample        15.116           ms/op
Client.createUser:createUser·p0.99    sample        22.751           ms/op
Client.createUser:createUser·p0.999   sample        25.592           ms/op
Client.createUser:createUser·p0.9999  sample        25.657           ms/op
Client.createUser:createUser·p1.00    sample        25.657           ms/op
Client.existUser                      sample  6344   5.042 ± 0.109   ms/op
Client.existUser:existUser·p0.00      sample         1.280           ms/op
Client.existUser:existUser·p0.50      sample         4.669           ms/op
Client.existUser:existUser·p0.90      sample         5.554           ms/op
Client.existUser:existUser·p0.95      sample         6.930           ms/op
Client.existUser:existUser·p0.99      sample        15.705           ms/op
Client.existUser:existUser·p0.999     sample        35.301           ms/op
Client.existUser:existUser·p0.9999    sample        35.652           ms/op
Client.existUser:existUser·p1.00      sample        35.652           ms/op
Client.getUser                        sample  5171   6.319 ± 0.144   ms/op
Client.getUser:getUser·p0.00          sample         1.898           ms/op
Client.getUser:getUser·p0.50          sample         5.792           ms/op
Client.getUser:getUser·p0.90          sample         7.930           ms/op
Client.getUser:getUser·p0.95          sample         9.044           ms/op
Client.getUser:getUser·p0.99          sample        19.104           ms/op
Client.getUser:getUser·p0.999         sample        37.148           ms/op
Client.getUser:getUser·p0.9999        sample        38.339           ms/op
Client.getUser:getUser·p1.00          sample        38.339           ms/op
Client.listUser                       sample  1374  23.625 ± 0.405   ms/op
Client.listUser:listUser·p0.00        sample         5.988           ms/op
Client.listUser:listUser·p0.50        sample        22.118           ms/op
Client.listUser:listUser·p0.90        sample        30.474           ms/op
Client.listUser:listUser·p0.95        sample        33.948           ms/op
Client.listUser:listUser·p0.99        sample        40.370           ms/op
Client.listUser:listUser·p0.999       sample        42.205           ms/op
Client.listUser:listUser·p0.9999      sample        42.402           ms/op
Client.listUser:listUser·p1.00        sample        42.402           ms/op
