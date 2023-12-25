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
# Warmup Iteration   1: 2.045 ops/ms
Iteration   1: 6.226 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.226 ops/ms


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
# Warmup Iteration   1: 6.686 ops/ms
Iteration   1: 13.075 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.075 ops/ms


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
# Warmup Iteration   1: 3.933 ops/ms
Iteration   1: 8.429 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.429 ops/ms


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
# Warmup Iteration   1: 1.901 ops/ms
Iteration   1: 3.504 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.504 ops/ms


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
# Warmup Iteration   1: 5.353 ±(99.9%) 0.075 ms/op
Iteration   1: 3.037 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.037 ms/op


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
# Warmup Iteration   1: 2.962 ±(99.9%) 0.035 ms/op
Iteration   1: 1.811 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.811 ms/op


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
# Warmup Iteration   1: 4.690 ±(99.9%) 0.065 ms/op
Iteration   1: 3.084 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.084 ms/op


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
# Warmup Iteration   1: 11.463 ±(99.9%) 0.272 ms/op
Iteration   1: 8.251 ±(99.9%) 0.129 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.251 ms/op


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
# Warmup Iteration   1: 4.932 ±(99.9%) 0.117 ms/op
Iteration   1: 3.297 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.414 ms/op
                 createUser·p0.999:  13.550 ms/op
                 createUser·p0.9999: 13.976 ms/op
                 createUser·p1.00:   13.976 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9720
  mean =      3.297 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 762 
    [ 2.500,  3.750) = 7350 
    [ 3.750,  5.000) = 1435 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     13.550 ms/op
     p(99.9900) =     13.976 ms/op
     p(99.9990) =     13.976 ms/op
     p(99.9999) =     13.976 ms/op
    p(100.0000) =     13.976 ms/op


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
# Warmup Iteration   1: 3.001 ±(99.9%) 0.071 ms/op
Iteration   1: 1.696 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.310 ms/op
                 existUser·p0.50:   1.642 ms/op
                 existUser·p0.90:   2.290 ms/op
                 existUser·p0.95:   2.511 ms/op
                 existUser·p0.99:   2.961 ms/op
                 existUser·p0.999:  5.439 ms/op
                 existUser·p0.9999: 7.023 ms/op
                 existUser·p1.00:   7.356 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18835
  mean =      1.696 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 12 
    [0.500, 1.000) = 662 
    [1.000, 1.500) = 5680 
    [1.500, 2.000) = 8260 
    [2.000, 2.500) = 3237 
    [2.500, 3.000) = 810 
    [3.000, 3.500) = 84 
    [3.500, 4.000) = 19 
    [4.000, 4.500) = 6 
    [4.500, 5.000) = 21 
    [5.000, 5.500) = 30 
    [5.500, 6.000) = 10 
    [6.000, 6.500) = 2 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.310 ms/op
     p(50.0000) =      1.642 ms/op
     p(90.0000) =      2.290 ms/op
     p(95.0000) =      2.511 ms/op
     p(99.0000) =      2.961 ms/op
     p(99.9000) =      5.439 ms/op
     p(99.9900) =      7.023 ms/op
     p(99.9990) =      7.356 ms/op
     p(99.9999) =      7.356 ms/op
    p(100.0000) =      7.356 ms/op


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
# Warmup Iteration   1: 4.487 ±(99.9%) 0.110 ms/op
Iteration   1: 3.252 ±(99.9%) 0.068 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  38.404 ms/op
                 getUser·p0.9999: 43.319 ms/op
                 getUser·p1.00:   43.319 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9827
  mean =      3.252 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9591 
    [ 5.000, 10.000) = 195 
    [10.000, 15.000) = 5 
    [15.000, 20.000) = 2 
    [20.000, 25.000) = 6 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 19 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.013 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     38.404 ms/op
     p(99.9900) =     43.319 ms/op
     p(99.9990) =     43.319 ms/op
     p(99.9999) =     43.319 ms/op
    p(100.0000) =     43.319 ms/op


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
# Warmup Iteration   1: 12.109 ±(99.9%) 0.406 ms/op
Iteration   1: 8.595 ±(99.9%) 0.127 ms/op
                 listUser·p0.00:   1.673 ms/op
                 listUser·p0.50:   8.217 ms/op
                 listUser·p0.90:   11.764 ms/op
                 listUser·p0.95:   12.878 ms/op
                 listUser·p0.99:   15.635 ms/op
                 listUser·p0.999:  23.877 ms/op
                 listUser·p0.9999: 27.329 ms/op
                 listUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3717
  mean =      8.595 ±(99.9%) 0.127 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 95 
    [ 5.000,  7.500) = 1149 
    [ 7.500, 10.000) = 1703 
    [10.000, 12.500) = 527 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.673 ms/op
     p(50.0000) =      8.217 ms/op
     p(90.0000) =     11.764 ms/op
     p(95.0000) =     12.878 ms/op
     p(99.0000) =     15.635 ms/op
     p(99.9000) =     23.877 ms/op
     p(99.9900) =     27.329 ms/op
     p(99.9990) =     27.329 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.226          ops/ms
Client.existUser                       thrpt         13.075          ops/ms
Client.getUser                         thrpt          8.429          ops/ms
Client.listUser                        thrpt          3.504          ops/ms
Client.createUser                       avgt          3.037           ms/op
Client.existUser                        avgt          1.811           ms/op
Client.getUser                          avgt          3.084           ms/op
Client.listUser                         avgt          8.251           ms/op
Client.createUser                     sample   9720   3.297 ± 0.029   ms/op
Client.createUser:createUser·p0.00    sample          0.831           ms/op
Client.createUser:createUser·p0.50    sample          3.183           ms/op
Client.createUser:createUser·p0.90    sample          3.973           ms/op
Client.createUser:createUser·p0.95    sample          4.268           ms/op
Client.createUser:createUser·p0.99    sample          6.414           ms/op
Client.createUser:createUser·p0.999   sample         13.550           ms/op
Client.createUser:createUser·p0.9999  sample         13.976           ms/op
Client.createUser:createUser·p1.00    sample         13.976           ms/op
Client.existUser                      sample  18835   1.696 ± 0.012   ms/op
Client.existUser:existUser·p0.00      sample          0.310           ms/op
Client.existUser:existUser·p0.50      sample          1.642           ms/op
Client.existUser:existUser·p0.90      sample          2.290           ms/op
Client.existUser:existUser·p0.95      sample          2.511           ms/op
Client.existUser:existUser·p0.99      sample          2.961           ms/op
Client.existUser:existUser·p0.999     sample          5.439           ms/op
Client.existUser:existUser·p0.9999    sample          7.023           ms/op
Client.existUser:existUser·p1.00      sample          7.356           ms/op
Client.getUser                        sample   9827   3.252 ± 0.068   ms/op
Client.getUser:getUser·p0.00          sample          1.013           ms/op
Client.getUser:getUser·p0.50          sample          3.105           ms/op
Client.getUser:getUser·p0.90          sample          3.920           ms/op
Client.getUser:getUser·p0.95          sample          4.317           ms/op
Client.getUser:getUser·p0.99          sample          6.472           ms/op
Client.getUser:getUser·p0.999         sample         38.404           ms/op
Client.getUser:getUser·p0.9999        sample         43.319           ms/op
Client.getUser:getUser·p1.00          sample         43.319           ms/op
Client.listUser                       sample   3717   8.595 ± 0.127   ms/op
Client.listUser:listUser·p0.00        sample          1.673           ms/op
Client.listUser:listUser·p0.50        sample          8.217           ms/op
Client.listUser:listUser·p0.90        sample         11.764           ms/op
Client.listUser:listUser·p0.95        sample         12.878           ms/op
Client.listUser:listUser·p0.99        sample         15.635           ms/op
Client.listUser:listUser·p0.999       sample         23.877           ms/op
Client.listUser:listUser·p0.9999      sample         27.329           ms/op
Client.listUser:listUser·p1.00        sample         27.329           ms/op
