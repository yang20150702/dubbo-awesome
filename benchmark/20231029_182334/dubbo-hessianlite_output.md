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
# Warmup Iteration   1: 1.435 ops/ms
Iteration   1: 4.130 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.130 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.318 ops/ms
Iteration   1: 10.179 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.179 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.149 ops/ms
Iteration   1: 6.720 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.720 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.135 ops/ms
Iteration   1: 1.778 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.778 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 9.357 ±(99.9%) 0.165 ms/op
Iteration   1: 3.760 ±(99.9%) 0.055 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.760 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.912 ±(99.9%) 0.082 ms/op
Iteration   1: 2.612 ±(99.9%) 0.048 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.612 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.848 ±(99.9%) 0.165 ms/op
Iteration   1: 5.437 ±(99.9%) 0.045 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.437 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 21.857 ±(99.9%) 0.622 ms/op
Iteration   1: 13.381 ±(99.9%) 0.253 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  13.381 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.111 ±(99.9%) 0.250 ms/op
Iteration   1: 3.336 ±(99.9%) 0.097 ms/op
                 createUser·p0.00:   1.077 ms/op
                 createUser·p0.50:   2.482 ms/op
                 createUser·p0.90:   4.801 ms/op
                 createUser·p0.95:   7.616 ms/op
                 createUser·p0.99:   12.370 ms/op
                 createUser·p0.999:  36.027 ms/op
                 createUser·p0.9999: 38.404 ms/op
                 createUser·p1.00:   38.404 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9545
  mean =      3.336 ±(99.9%) 0.097 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4916 
    [ 2.500,  5.000) = 3782 
    [ 5.000,  7.500) = 346 
    [ 7.500, 10.000) = 281 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      7.616 ms/op
     p(99.0000) =     12.370 ms/op
     p(99.9000) =     36.027 ms/op
     p(99.9900) =     38.404 ms/op
     p(99.9990) =     38.404 ms/op
     p(99.9999) =     38.404 ms/op
    p(100.0000) =     38.404 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 4.805 ±(99.9%) 0.169 ms/op
Iteration   1: 1.808 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   1.741 ms/op
                 existUser·p0.90:   2.048 ms/op
                 existUser·p0.95:   2.212 ms/op
                 existUser·p0.99:   6.038 ms/op
                 existUser·p0.999:  20.260 ms/op
                 existUser·p0.9999: 21.337 ms/op
                 existUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17692
  mean =      1.808 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17190 
    [ 2.500,  5.000) = 305 
    [ 5.000,  7.500) = 64 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      1.741 ms/op
     p(90.0000) =      2.048 ms/op
     p(95.0000) =      2.212 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     20.260 ms/op
     p(99.9900) =     21.337 ms/op
     p(99.9990) =     22.118 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 7.208 ±(99.9%) 0.238 ms/op
Iteration   1: 2.953 ±(99.9%) 0.047 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   2.634 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   9.519 ms/op
                 getUser·p0.999:  21.299 ms/op
                 getUser·p0.9999: 23.902 ms/op
                 getUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10832
  mean =      2.953 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4079 
    [ 2.500,  5.000) = 6256 
    [ 5.000,  7.500) = 302 
    [ 7.500, 10.000) = 112 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      9.519 ms/op
     p(99.9000) =     21.299 ms/op
     p(99.9900) =     23.902 ms/op
     p(99.9990) =     23.953 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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
# Warmup Iteration   1: 19.916 ±(99.9%) 0.733 ms/op
Iteration   1: 10.690 ±(99.9%) 0.181 ms/op
                 listUser·p0.00:   2.839 ms/op
                 listUser·p0.50:   10.224 ms/op
                 listUser·p0.90:   13.790 ms/op
                 listUser·p0.95:   15.916 ms/op
                 listUser·p0.99:   24.021 ms/op
                 listUser·p0.999:  27.231 ms/op
                 listUser·p0.9999: 27.886 ms/op
                 listUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2992
  mean =     10.690 ±(99.9%) 0.181 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 25 
    [ 5.000,  7.500) = 219 
    [ 7.500, 10.000) = 1087 
    [10.000, 12.500) = 1171 
    [12.500, 15.000) = 297 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      2.839 ms/op
     p(50.0000) =     10.224 ms/op
     p(90.0000) =     13.790 ms/op
     p(95.0000) =     15.916 ms/op
     p(99.0000) =     24.021 ms/op
     p(99.9000) =     27.231 ms/op
     p(99.9900) =     27.886 ms/op
     p(99.9990) =     27.886 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# Run complete. Total time: 00:01:30

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          4.130          ops/ms
Client.existUser                       thrpt         10.179          ops/ms
Client.getUser                         thrpt          6.720          ops/ms
Client.listUser                        thrpt          1.778          ops/ms
Client.createUser                       avgt          3.760           ms/op
Client.existUser                        avgt          2.612           ms/op
Client.getUser                          avgt          5.437           ms/op
Client.listUser                         avgt         13.381           ms/op
Client.createUser                     sample   9545   3.336 ± 0.097   ms/op
Client.createUser:createUser·p0.00    sample          1.077           ms/op
Client.createUser:createUser·p0.50    sample          2.482           ms/op
Client.createUser:createUser·p0.90    sample          4.801           ms/op
Client.createUser:createUser·p0.95    sample          7.616           ms/op
Client.createUser:createUser·p0.99    sample         12.370           ms/op
Client.createUser:createUser·p0.999   sample         36.027           ms/op
Client.createUser:createUser·p0.9999  sample         38.404           ms/op
Client.createUser:createUser·p1.00    sample         38.404           ms/op
Client.existUser                      sample  17692   1.808 ± 0.029   ms/op
Client.existUser:existUser·p0.00      sample          0.690           ms/op
Client.existUser:existUser·p0.50      sample          1.741           ms/op
Client.existUser:existUser·p0.90      sample          2.048           ms/op
Client.existUser:existUser·p0.95      sample          2.212           ms/op
Client.existUser:existUser·p0.99      sample          6.038           ms/op
Client.existUser:existUser·p0.999     sample         20.260           ms/op
Client.existUser:existUser·p0.9999    sample         21.337           ms/op
Client.existUser:existUser·p1.00      sample         22.118           ms/op
Client.getUser                        sample  10832   2.953 ± 0.047   ms/op
Client.getUser:getUser·p0.00          sample          1.133           ms/op
Client.getUser:getUser·p0.50          sample          2.634           ms/op
Client.getUser:getUser·p0.90          sample          3.768           ms/op
Client.getUser:getUser·p0.95          sample          4.866           ms/op
Client.getUser:getUser·p0.99          sample          9.519           ms/op
Client.getUser:getUser·p0.999         sample         21.299           ms/op
Client.getUser:getUser·p0.9999        sample         23.902           ms/op
Client.getUser:getUser·p1.00          sample         23.953           ms/op
Client.listUser                       sample   2992  10.690 ± 0.181   ms/op
Client.listUser:listUser·p0.00        sample          2.839           ms/op
Client.listUser:listUser·p0.50        sample         10.224           ms/op
Client.listUser:listUser·p0.90        sample         13.790           ms/op
Client.listUser:listUser·p0.95        sample         15.916           ms/op
Client.listUser:listUser·p0.99        sample         24.021           ms/op
Client.listUser:listUser·p0.999       sample         27.231           ms/op
Client.listUser:listUser·p0.9999      sample         27.886           ms/op
Client.listUser:listUser·p1.00        sample         27.886           ms/op
