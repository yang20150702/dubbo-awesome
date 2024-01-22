# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.217 ops/ms
Iteration   1: 6.326 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.326 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.630 ops/ms
Iteration   1: 10.112 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.112 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.846 ops/ms
Iteration   1: 8.303 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.303 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.231 ops/ms
Iteration   1: 3.699 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.699 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.654 ±(99.9%) 0.081 ms/op
Iteration   1: 2.950 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.950 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.184 ±(99.9%) 0.034 ms/op
Iteration   1: 1.804 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.804 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.324 ±(99.9%) 0.083 ms/op
Iteration   1: 2.546 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.546 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.142 ±(99.9%) 0.168 ms/op
Iteration   1: 8.862 ±(99.9%) 0.100 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.862 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.030 ±(99.9%) 0.103 ms/op
Iteration   1: 3.119 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   6.157 ms/op
                 createUser·p0.999:  22.540 ms/op
                 createUser·p0.9999: 23.132 ms/op
                 createUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10372
  mean =      3.119 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2243 
    [ 2.500,  5.000) = 7896 
    [ 5.000,  7.500) = 169 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.157 ms/op
     p(99.9000) =     22.540 ms/op
     p(99.9900) =     23.132 ms/op
     p(99.9990) =     23.134 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.020 ±(99.9%) 0.067 ms/op
Iteration   1: 1.657 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.529 ms/op
                 existUser·p0.50:   1.581 ms/op
                 existUser·p0.90:   2.023 ms/op
                 existUser·p0.95:   2.204 ms/op
                 existUser·p0.99:   2.928 ms/op
                 existUser·p0.999:  3.780 ms/op
                 existUser·p0.9999: 4.670 ms/op
                 existUser·p1.00:   5.464 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19316
  mean =      1.657 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 56 
    [1.000, 1.500) = 6066 
    [1.500, 2.000) = 11082 
    [2.000, 2.500) = 1629 
    [2.500, 3.000) = 319 
    [3.000, 3.500) = 112 
    [3.500, 4.000) = 37 
    [4.000, 4.500) = 9 
    [4.500, 5.000) = 5 
    [5.000, 5.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      1.581 ms/op
     p(90.0000) =      2.023 ms/op
     p(95.0000) =      2.204 ms/op
     p(99.0000) =      2.928 ms/op
     p(99.9000) =      3.780 ms/op
     p(99.9900) =      4.670 ms/op
     p(99.9990) =      5.464 ms/op
     p(99.9999) =      5.464 ms/op
    p(100.0000) =      5.464 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.639 ±(99.9%) 0.128 ms/op
Iteration   1: 2.940 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.593 ms/op
                 getUser·p0.50:   2.851 ms/op
                 getUser·p0.90:   3.729 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  6.964 ms/op
                 getUser·p0.9999: 7.891 ms/op
                 getUser·p1.00:   7.938 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10865
  mean =      2.940 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 15 
    [1.000, 1.500) = 23 
    [1.500, 2.000) = 164 
    [2.000, 2.500) = 3385 
    [2.500, 3.000) = 2788 
    [3.000, 3.500) = 2615 
    [3.500, 4.000) = 1302 
    [4.000, 4.500) = 277 
    [4.500, 5.000) = 74 
    [5.000, 5.500) = 62 
    [5.500, 6.000) = 47 
    [6.000, 6.500) = 81 
    [6.500, 7.000) = 24 
    [7.000, 7.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.729 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =      6.964 ms/op
     p(99.9900) =      7.891 ms/op
     p(99.9990) =      7.938 ms/op
     p(99.9999) =      7.938 ms/op
    p(100.0000) =      7.938 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.701 ±(99.9%) 0.475 ms/op
Iteration   1: 7.595 ±(99.9%) 0.153 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   7.053 ms/op
                 listUser·p0.90:   10.093 ms/op
                 listUser·p0.95:   11.092 ms/op
                 listUser·p0.99:   19.202 ms/op
                 listUser·p0.999:  33.935 ms/op
                 listUser·p0.9999: 34.472 ms/op
                 listUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4191
  mean =      7.595 ±(99.9%) 0.153 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 273 
    [ 5.000,  7.500) = 2297 
    [ 7.500, 10.000) = 1179 
    [10.000, 12.500) = 309 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.220 ms/op
     p(50.0000) =      7.053 ms/op
     p(90.0000) =     10.093 ms/op
     p(95.0000) =     11.092 ms/op
     p(99.0000) =     19.202 ms/op
     p(99.9000) =     33.935 ms/op
     p(99.9900) =     34.472 ms/op
     p(99.9990) =     34.472 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.326          ops/ms
Client.existUser                       thrpt         10.112          ops/ms
Client.getUser                         thrpt          8.303          ops/ms
Client.listUser                        thrpt          3.699          ops/ms
Client.createUser                       avgt          2.950           ms/op
Client.existUser                        avgt          1.804           ms/op
Client.getUser                          avgt          2.546           ms/op
Client.listUser                         avgt          8.862           ms/op
Client.createUser                     sample  10372   3.119 ± 0.045   ms/op
Client.createUser:createUser·p0.00    sample          1.161           ms/op
Client.createUser:createUser·p0.50    sample          2.953           ms/op
Client.createUser:createUser·p0.90    sample          3.985           ms/op
Client.createUser:createUser·p0.95    sample          4.334           ms/op
Client.createUser:createUser·p0.99    sample          6.157           ms/op
Client.createUser:createUser·p0.999   sample         22.540           ms/op
Client.createUser:createUser·p0.9999  sample         23.132           ms/op
Client.createUser:createUser·p1.00    sample         23.134           ms/op
Client.existUser                      sample  19316   1.657 ± 0.008   ms/op
Client.existUser:existUser·p0.00      sample          0.529           ms/op
Client.existUser:existUser·p0.50      sample          1.581           ms/op
Client.existUser:existUser·p0.90      sample          2.023           ms/op
Client.existUser:existUser·p0.95      sample          2.204           ms/op
Client.existUser:existUser·p0.99      sample          2.928           ms/op
Client.existUser:existUser·p0.999     sample          3.780           ms/op
Client.existUser:existUser·p0.9999    sample          4.670           ms/op
Client.existUser:existUser·p1.00      sample          5.464           ms/op
Client.getUser                        sample  10865   2.940 ± 0.023   ms/op
Client.getUser:getUser·p0.00          sample          0.593           ms/op
Client.getUser:getUser·p0.50          sample          2.851           ms/op
Client.getUser:getUser·p0.90          sample          3.729           ms/op
Client.getUser:getUser·p0.95          sample          4.030           ms/op
Client.getUser:getUser·p0.99          sample          6.046           ms/op
Client.getUser:getUser·p0.999         sample          6.964           ms/op
Client.getUser:getUser·p0.9999        sample          7.891           ms/op
Client.getUser:getUser·p1.00          sample          7.938           ms/op
Client.listUser                       sample   4191   7.595 ± 0.153   ms/op
Client.listUser:listUser·p0.00        sample          2.220           ms/op
Client.listUser:listUser·p0.50        sample          7.053           ms/op
Client.listUser:listUser·p0.90        sample         10.093           ms/op
Client.listUser:listUser·p0.95        sample         11.092           ms/op
Client.listUser:listUser·p0.99        sample         19.202           ms/op
Client.listUser:listUser·p0.999       sample         33.935           ms/op
Client.listUser:listUser·p0.9999      sample         34.472           ms/op
Client.listUser:listUser·p1.00        sample         34.472           ms/op
