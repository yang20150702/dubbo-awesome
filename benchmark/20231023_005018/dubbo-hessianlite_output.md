# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.490 ops/ms
Iteration   1: 3.621 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.621 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.309 ops/ms
Iteration   1: 10.429 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.429 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 2.741 ops/ms
Iteration   1: 4.939 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.939 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.042 ops/ms
Iteration   1: 1.363 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.363 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 9.501 ±(99.9%) 0.243 ms/op
Iteration   1: 4.729 ±(99.9%) 0.070 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.729 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.195 ±(99.9%) 0.076 ms/op
Iteration   1: 2.472 ±(99.9%) 0.043 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.472 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.062 ±(99.9%) 0.183 ms/op
Iteration   1: 5.622 ±(99.9%) 0.113 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.622 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 27.676 ±(99.9%) 1.032 ms/op
Iteration   1: 19.931 ±(99.9%) 0.175 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  19.931 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.713 ±(99.9%) 0.282 ms/op
Iteration   1: 3.922 ±(99.9%) 0.080 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   5.464 ms/op
                 createUser·p0.95:   6.345 ms/op
                 createUser·p0.99:   15.447 ms/op
                 createUser·p0.999:  25.559 ms/op
                 createUser·p0.9999: 26.051 ms/op
                 createUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 8169
  mean =      3.922 ±(99.9%) 0.080 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 85 
    [ 2.500,  5.000) = 7077 
    [ 5.000,  7.500) = 741 
    [ 7.500, 10.000) = 98 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      5.464 ms/op
     p(95.0000) =      6.345 ms/op
     p(99.0000) =     15.447 ms/op
     p(99.9000) =     25.559 ms/op
     p(99.9900) =     26.051 ms/op
     p(99.9990) =     26.051 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.484 ±(99.9%) 0.255 ms/op
Iteration   1: 2.546 ±(99.9%) 0.059 ms/op
                 existUser·p0.00:   0.546 ms/op
                 existUser·p0.50:   1.987 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   6.619 ms/op
                 existUser·p0.99:   10.797 ms/op
                 existUser·p0.999:  23.921 ms/op
                 existUser·p0.9999: 24.482 ms/op
                 existUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 12564
  mean =      2.546 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10348 
    [ 2.500,  5.000) = 1303 
    [ 5.000,  7.500) = 466 
    [ 7.500, 10.000) = 245 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      1.987 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      6.619 ms/op
     p(99.0000) =     10.797 ms/op
     p(99.9000) =     23.921 ms/op
     p(99.9900) =     24.482 ms/op
     p(99.9990) =     24.642 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 8.542 ±(99.9%) 0.257 ms/op
Iteration   1: 3.476 ±(99.9%) 0.062 ms/op
                 getUser·p0.00:   0.648 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   4.338 ms/op
                 getUser·p0.95:   5.595 ms/op
                 getUser·p0.99:   11.952 ms/op
                 getUser·p0.999:  20.538 ms/op
                 getUser·p0.9999: 21.365 ms/op
                 getUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9223
  mean =      3.476 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1284 
    [ 2.500,  5.000) = 7294 
    [ 5.000,  7.500) = 375 
    [ 7.500, 10.000) = 88 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      4.338 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =     11.952 ms/op
     p(99.9000) =     20.538 ms/op
     p(99.9900) =     21.365 ms/op
     p(99.9990) =     21.365 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 22.664 ±(99.9%) 0.843 ms/op
Iteration   1: 18.953 ±(99.9%) 0.428 ms/op
                 listUser·p0.00:   5.104 ms/op
                 listUser·p0.50:   18.579 ms/op
                 listUser·p0.90:   25.723 ms/op
                 listUser·p0.95:   28.049 ms/op
                 listUser·p0.99:   32.178 ms/op
                 listUser·p0.999:  58.954 ms/op
                 listUser·p0.9999: 113.902 ms/op
                 listUser·p1.00:   113.902 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1764
  mean =     18.953 ±(99.9%) 0.428 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 150 
    [ 12.500,  25.000) = 1402 
    [ 25.000,  37.500) = 209 
    [ 37.500,  50.000) = 2 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 0 
    [112.500, 125.000) = 1 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      5.104 ms/op
     p(50.0000) =     18.579 ms/op
     p(90.0000) =     25.723 ms/op
     p(95.0000) =     28.049 ms/op
     p(99.0000) =     32.178 ms/op
     p(99.9000) =     58.954 ms/op
     p(99.9900) =    113.902 ms/op
     p(99.9990) =    113.902 ms/op
     p(99.9999) =    113.902 ms/op
    p(100.0000) =    113.902 ms/op


# Run complete. Total time: 00:01:32

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt    Score   Error   Units
Client.createUser                      thrpt           3.621          ops/ms
Client.existUser                       thrpt          10.429          ops/ms
Client.getUser                         thrpt           4.939          ops/ms
Client.listUser                        thrpt           1.363          ops/ms
Client.createUser                       avgt           4.729           ms/op
Client.existUser                        avgt           2.472           ms/op
Client.getUser                          avgt           5.622           ms/op
Client.listUser                         avgt          19.931           ms/op
Client.createUser                     sample   8169    3.922 ± 0.080   ms/op
Client.createUser:createUser·p0.00    sample           0.882           ms/op
Client.createUser:createUser·p0.50    sample           3.293           ms/op
Client.createUser:createUser·p0.90    sample           5.464           ms/op
Client.createUser:createUser·p0.95    sample           6.345           ms/op
Client.createUser:createUser·p0.99    sample          15.447           ms/op
Client.createUser:createUser·p0.999   sample          25.559           ms/op
Client.createUser:createUser·p0.9999  sample          26.051           ms/op
Client.createUser:createUser·p1.00    sample          26.051           ms/op
Client.existUser                      sample  12564    2.546 ± 0.059   ms/op
Client.existUser:existUser·p0.00      sample           0.546           ms/op
Client.existUser:existUser·p0.50      sample           1.987           ms/op
Client.existUser:existUser·p0.90      sample           3.625           ms/op
Client.existUser:existUser·p0.95      sample           6.619           ms/op
Client.existUser:existUser·p0.99      sample          10.797           ms/op
Client.existUser:existUser·p0.999     sample          23.921           ms/op
Client.existUser:existUser·p0.9999    sample          24.482           ms/op
Client.existUser:existUser·p1.00      sample          24.642           ms/op
Client.getUser                        sample   9223    3.476 ± 0.062   ms/op
Client.getUser:getUser·p0.00          sample           0.648           ms/op
Client.getUser:getUser·p0.50          sample           3.166           ms/op
Client.getUser:getUser·p0.90          sample           4.338           ms/op
Client.getUser:getUser·p0.95          sample           5.595           ms/op
Client.getUser:getUser·p0.99          sample          11.952           ms/op
Client.getUser:getUser·p0.999         sample          20.538           ms/op
Client.getUser:getUser·p0.9999        sample          21.365           ms/op
Client.getUser:getUser·p1.00          sample          21.365           ms/op
Client.listUser                       sample   1764   18.953 ± 0.428   ms/op
Client.listUser:listUser·p0.00        sample           5.104           ms/op
Client.listUser:listUser·p0.50        sample          18.579           ms/op
Client.listUser:listUser·p0.90        sample          25.723           ms/op
Client.listUser:listUser·p0.95        sample          28.049           ms/op
Client.listUser:listUser·p0.99        sample          32.178           ms/op
Client.listUser:listUser·p0.999       sample          58.954           ms/op
Client.listUser:listUser·p0.9999      sample         113.902           ms/op
Client.listUser:listUser·p1.00        sample         113.902           ms/op
