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
# Warmup Iteration   1: 1.266 ops/ms
Iteration   1: 2.091 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.091 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 2.338 ops/ms
Iteration   1: 6.091 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.091 ops/ms


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
# Warmup Iteration   1: 2.174 ops/ms
Iteration   1: 4.176 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.176 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.911 ops/ms
Iteration   1: 1.410 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.410 ops/ms


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
# Warmup Iteration   1: 17.206 ±(99.9%) 0.271 ms/op
Iteration   1: 7.843 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.843 ms/op


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
# Warmup Iteration   1: 7.666 ±(99.9%) 0.089 ms/op
Iteration   1: 4.047 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.047 ms/op


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
# Warmup Iteration   1: 11.241 ±(99.9%) 0.470 ms/op
Iteration   1: 5.362 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.362 ms/op


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
# Warmup Iteration   1: 31.627 ±(99.9%) 0.684 ms/op
Iteration   1: 23.085 ±(99.9%) 0.155 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  23.085 ms/op


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
# Warmup Iteration   1: 12.605 ±(99.9%) 0.336 ms/op
Iteration   1: 6.571 ±(99.9%) 0.114 ms/op
                 createUser·p0.00:   2.634 ms/op
                 createUser·p0.50:   6.398 ms/op
                 createUser·p0.90:   6.939 ms/op
                 createUser·p0.95:   9.964 ms/op
                 createUser·p0.99:   17.826 ms/op
                 createUser·p0.999:  25.068 ms/op
                 createUser·p0.9999: 25.494 ms/op
                 createUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4916
  mean =      6.571 ±(99.9%) 0.114 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 560 
    [ 5.000,  7.500) = 4020 
    [ 7.500, 10.000) = 92 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      2.634 ms/op
     p(50.0000) =      6.398 ms/op
     p(90.0000) =      6.939 ms/op
     p(95.0000) =      9.964 ms/op
     p(99.0000) =     17.826 ms/op
     p(99.9000) =     25.068 ms/op
     p(99.9900) =     25.494 ms/op
     p(99.9990) =     25.494 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 6.867 ±(99.9%) 0.185 ms/op
Iteration   1: 3.956 ±(99.9%) 0.074 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   4.317 ms/op
                 existUser·p0.90:   4.997 ms/op
                 existUser·p0.95:   5.997 ms/op
                 existUser·p0.99:   12.501 ms/op
                 existUser·p0.999:  21.067 ms/op
                 existUser·p0.9999: 21.299 ms/op
                 existUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8080
  mean =      3.956 ±(99.9%) 0.074 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2173 
    [ 2.500,  5.000) = 5111 
    [ 5.000,  7.500) = 481 
    [ 7.500, 10.000) = 182 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      4.317 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =     12.501 ms/op
     p(99.9000) =     21.067 ms/op
     p(99.9900) =     21.299 ms/op
     p(99.9990) =     21.299 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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
# Warmup Iteration   1: 11.318 ±(99.9%) 0.363 ms/op
Iteration   1: 4.698 ±(99.9%) 0.047 ms/op
                 getUser·p0.00:   1.407 ms/op
                 getUser·p0.50:   4.571 ms/op
                 getUser·p0.90:   5.382 ms/op
                 getUser·p0.95:   5.726 ms/op
                 getUser·p0.99:   8.503 ms/op
                 getUser·p0.999:  19.565 ms/op
                 getUser·p0.9999: 19.890 ms/op
                 getUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6964
  mean =      4.698 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 42 
    [ 2.500,  3.750) = 323 
    [ 3.750,  5.000) = 5202 
    [ 5.000,  6.250) = 1191 
    [ 6.250,  7.500) = 104 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.407 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      5.382 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      8.503 ms/op
     p(99.9000) =     19.565 ms/op
     p(99.9900) =     19.890 ms/op
     p(99.9990) =     19.890 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 28.302 ±(99.9%) 0.787 ms/op
Iteration   1: 18.047 ±(99.9%) 0.336 ms/op
                 listUser·p0.00:   5.128 ms/op
                 listUser·p0.50:   17.891 ms/op
                 listUser·p0.90:   22.315 ms/op
                 listUser·p0.95:   26.234 ms/op
                 listUser·p0.99:   32.440 ms/op
                 listUser·p0.999:  40.315 ms/op
                 listUser·p0.9999: 40.567 ms/op
                 listUser·p1.00:   40.567 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1767
  mean =     18.047 ±(99.9%) 0.336 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 28 
    [10.000, 15.000) = 381 
    [15.000, 20.000) = 947 
    [20.000, 25.000) = 299 
    [25.000, 30.000) = 78 
    [30.000, 35.000) = 27 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      5.128 ms/op
     p(50.0000) =     17.891 ms/op
     p(90.0000) =     22.315 ms/op
     p(95.0000) =     26.234 ms/op
     p(99.0000) =     32.440 ms/op
     p(99.9000) =     40.315 ms/op
     p(99.9900) =     40.567 ms/op
     p(99.9990) =     40.567 ms/op
     p(99.9999) =     40.567 ms/op
    p(100.0000) =     40.567 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.091          ops/ms
Client.existUser                       thrpt         6.091          ops/ms
Client.getUser                         thrpt         4.176          ops/ms
Client.listUser                        thrpt         1.410          ops/ms
Client.createUser                       avgt         7.843           ms/op
Client.existUser                        avgt         4.047           ms/op
Client.getUser                          avgt         5.362           ms/op
Client.listUser                         avgt        23.085           ms/op
Client.createUser                     sample  4916   6.571 ± 0.114   ms/op
Client.createUser:createUser·p0.00    sample         2.634           ms/op
Client.createUser:createUser·p0.50    sample         6.398           ms/op
Client.createUser:createUser·p0.90    sample         6.939           ms/op
Client.createUser:createUser·p0.95    sample         9.964           ms/op
Client.createUser:createUser·p0.99    sample        17.826           ms/op
Client.createUser:createUser·p0.999   sample        25.068           ms/op
Client.createUser:createUser·p0.9999  sample        25.494           ms/op
Client.createUser:createUser·p1.00    sample        25.494           ms/op
Client.existUser                      sample  8080   3.956 ± 0.074   ms/op
Client.existUser:existUser·p0.00      sample         0.794           ms/op
Client.existUser:existUser·p0.50      sample         4.317           ms/op
Client.existUser:existUser·p0.90      sample         4.997           ms/op
Client.existUser:existUser·p0.95      sample         5.997           ms/op
Client.existUser:existUser·p0.99      sample        12.501           ms/op
Client.existUser:existUser·p0.999     sample        21.067           ms/op
Client.existUser:existUser·p0.9999    sample        21.299           ms/op
Client.existUser:existUser·p1.00      sample        21.299           ms/op
Client.getUser                        sample  6964   4.698 ± 0.047   ms/op
Client.getUser:getUser·p0.00          sample         1.407           ms/op
Client.getUser:getUser·p0.50          sample         4.571           ms/op
Client.getUser:getUser·p0.90          sample         5.382           ms/op
Client.getUser:getUser·p0.95          sample         5.726           ms/op
Client.getUser:getUser·p0.99          sample         8.503           ms/op
Client.getUser:getUser·p0.999         sample        19.565           ms/op
Client.getUser:getUser·p0.9999        sample        19.890           ms/op
Client.getUser:getUser·p1.00          sample        19.890           ms/op
Client.listUser                       sample  1767  18.047 ± 0.336   ms/op
Client.listUser:listUser·p0.00        sample         5.128           ms/op
Client.listUser:listUser·p0.50        sample        17.891           ms/op
Client.listUser:listUser·p0.90        sample        22.315           ms/op
Client.listUser:listUser·p0.95        sample        26.234           ms/op
Client.listUser:listUser·p0.99        sample        32.440           ms/op
Client.listUser:listUser·p0.999       sample        40.315           ms/op
Client.listUser:listUser·p0.9999      sample        40.567           ms/op
Client.listUser:listUser·p1.00        sample        40.567           ms/op
