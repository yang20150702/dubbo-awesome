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
# Warmup Iteration   1: 2.281 ops/ms
Iteration   1: 5.603 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.603 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.935 ops/ms
Iteration   1: 12.855 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.855 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.255 ops/ms
Iteration   1: 8.592 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.592 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.133 ops/ms
Iteration   1: 3.469 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.469 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.471 ±(99.9%) 0.074 ms/op
Iteration   1: 2.977 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.977 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.480 ±(99.9%) 0.040 ms/op
Iteration   1: 1.840 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.840 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.056 ±(99.9%) 0.063 ms/op
Iteration   1: 3.516 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.516 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.114 ±(99.9%) 0.257 ms/op
Iteration   1: 12.254 ±(99.9%) 0.224 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  12.254 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.602 ±(99.9%) 0.170 ms/op
Iteration   1: 3.148 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   1.587 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   9.804 ms/op
                 createUser·p0.999:  15.024 ms/op
                 createUser·p0.9999: 15.269 ms/op
                 createUser·p1.00:   15.270 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10158
  mean =      3.148 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2211 
    [ 2.500,  3.750) = 6837 
    [ 3.750,  5.000) = 766 
    [ 5.000,  6.250) = 136 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.587 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      9.804 ms/op
     p(99.9000) =     15.024 ms/op
     p(99.9900) =     15.269 ms/op
     p(99.9990) =     15.270 ms/op
     p(99.9999) =     15.270 ms/op
    p(100.0000) =     15.270 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.405 ±(99.9%) 0.081 ms/op
Iteration   1: 1.952 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.441 ms/op
                 existUser·p0.50:   1.800 ms/op
                 existUser·p0.90:   2.335 ms/op
                 existUser·p0.95:   2.548 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  21.168 ms/op
                 existUser·p0.9999: 21.579 ms/op
                 existUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16369
  mean =      1.952 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15376 
    [ 2.500,  5.000) = 839 
    [ 5.000,  7.500) = 87 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.441 ms/op
     p(50.0000) =      1.800 ms/op
     p(90.0000) =      2.335 ms/op
     p(95.0000) =      2.548 ms/op
     p(99.0000) =      4.661 ms/op
     p(99.9000) =     21.168 ms/op
     p(99.9900) =     21.579 ms/op
     p(99.9990) =     21.725 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.849 ±(99.9%) 0.123 ms/op
Iteration   1: 3.088 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   5.259 ms/op
                 getUser·p0.999:  7.257 ms/op
                 getUser·p0.9999: 8.840 ms/op
                 getUser·p1.00:   8.847 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10363
  mean =      3.088 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 25 
    [1.500, 2.000) = 188 
    [2.000, 2.500) = 1236 
    [2.500, 3.000) = 3394 
    [3.000, 3.500) = 3360 
    [3.500, 4.000) = 1633 
    [4.000, 4.500) = 305 
    [4.500, 5.000) = 83 
    [5.000, 5.500) = 67 
    [5.500, 6.000) = 29 
    [6.000, 6.500) = 14 
    [6.500, 7.000) = 12 
    [7.000, 7.500) = 10 
    [7.500, 8.000) = 2 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      5.259 ms/op
     p(99.9000) =      7.257 ms/op
     p(99.9900) =      8.840 ms/op
     p(99.9990) =      8.847 ms/op
     p(99.9999) =      8.847 ms/op
    p(100.0000) =      8.847 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.954 ±(99.9%) 0.368 ms/op
Iteration   1: 8.789 ±(99.9%) 0.151 ms/op
                 listUser·p0.00:   3.203 ms/op
                 listUser·p0.50:   8.331 ms/op
                 listUser·p0.90:   12.141 ms/op
                 listUser·p0.95:   13.042 ms/op
                 listUser·p0.99:   19.761 ms/op
                 listUser·p0.999:  26.435 ms/op
                 listUser·p0.9999: 37.421 ms/op
                 listUser·p1.00:   37.421 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3628
  mean =      8.789 ±(99.9%) 0.151 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 89 
    [ 5.000,  7.500) = 1199 
    [ 7.500, 10.000) = 1405 
    [10.000, 12.500) = 655 
    [12.500, 15.000) = 207 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      3.203 ms/op
     p(50.0000) =      8.331 ms/op
     p(90.0000) =     12.141 ms/op
     p(95.0000) =     13.042 ms/op
     p(99.0000) =     19.761 ms/op
     p(99.9000) =     26.435 ms/op
     p(99.9900) =     37.421 ms/op
     p(99.9990) =     37.421 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.603          ops/ms
Client.existUser                       thrpt         12.855          ops/ms
Client.getUser                         thrpt          8.592          ops/ms
Client.listUser                        thrpt          3.469          ops/ms
Client.createUser                       avgt          2.977           ms/op
Client.existUser                        avgt          1.840           ms/op
Client.getUser                          avgt          3.516           ms/op
Client.listUser                         avgt         12.254           ms/op
Client.createUser                     sample  10158   3.148 ± 0.041   ms/op
Client.createUser:createUser·p0.00    sample          1.587           ms/op
Client.createUser:createUser·p0.50    sample          2.953           ms/op
Client.createUser:createUser·p0.90    sample          3.793           ms/op
Client.createUser:createUser·p0.95    sample          4.162           ms/op
Client.createUser:createUser·p0.99    sample          9.804           ms/op
Client.createUser:createUser·p0.999   sample         15.024           ms/op
Client.createUser:createUser·p0.9999  sample         15.269           ms/op
Client.createUser:createUser·p1.00    sample         15.270           ms/op
Client.existUser                      sample  16369   1.952 ± 0.027   ms/op
Client.existUser:existUser·p0.00      sample          0.441           ms/op
Client.existUser:existUser·p0.50      sample          1.800           ms/op
Client.existUser:existUser·p0.90      sample          2.335           ms/op
Client.existUser:existUser·p0.95      sample          2.548           ms/op
Client.existUser:existUser·p0.99      sample          4.661           ms/op
Client.existUser:existUser·p0.999     sample         21.168           ms/op
Client.existUser:existUser·p0.9999    sample         21.579           ms/op
Client.existUser:existUser·p1.00      sample         21.725           ms/op
Client.getUser                        sample  10363   3.088 ± 0.020   ms/op
Client.getUser:getUser·p0.00          sample          1.128           ms/op
Client.getUser:getUser·p0.50          sample          3.043           ms/op
Client.getUser:getUser·p0.90          sample          3.777           ms/op
Client.getUser:getUser·p0.95          sample          4.010           ms/op
Client.getUser:getUser·p0.99          sample          5.259           ms/op
Client.getUser:getUser·p0.999         sample          7.257           ms/op
Client.getUser:getUser·p0.9999        sample          8.840           ms/op
Client.getUser:getUser·p1.00          sample          8.847           ms/op
Client.listUser                       sample   3628   8.789 ± 0.151   ms/op
Client.listUser:listUser·p0.00        sample          3.203           ms/op
Client.listUser:listUser·p0.50        sample          8.331           ms/op
Client.listUser:listUser·p0.90        sample         12.141           ms/op
Client.listUser:listUser·p0.95        sample         13.042           ms/op
Client.listUser:listUser·p0.99        sample         19.761           ms/op
Client.listUser:listUser·p0.999       sample         26.435           ms/op
Client.listUser:listUser·p0.9999      sample         37.421           ms/op
Client.listUser:listUser·p1.00        sample         37.421           ms/op
