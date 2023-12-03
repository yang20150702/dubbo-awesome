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
# Warmup Iteration   1: 2.323 ops/ms
Iteration   1: 6.090 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.090 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.199 ops/ms
Iteration   1: 12.029 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.029 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.383 ops/ms
Iteration   1: 9.456 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.456 ops/ms


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
# Warmup Iteration   1: 2.187 ops/ms
Iteration   1: 3.222 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.222 ops/ms


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
# Warmup Iteration   1: 5.742 ±(99.9%) 0.099 ms/op
Iteration   1: 3.173 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.173 ms/op


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
# Warmup Iteration   1: 2.984 ±(99.9%) 0.031 ms/op
Iteration   1: 1.792 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.792 ms/op


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
# Warmup Iteration   1: 4.888 ±(99.9%) 0.078 ms/op
Iteration   1: 3.282 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.282 ms/op


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
# Warmup Iteration   1: 13.558 ±(99.9%) 0.328 ms/op
Iteration   1: 8.507 ±(99.9%) 0.097 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.507 ms/op


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
# Warmup Iteration   1: 5.060 ±(99.9%) 0.122 ms/op
Iteration   1: 3.081 ±(99.9%) 0.069 ms/op
                 createUser·p0.00:   0.988 ms/op
                 createUser·p0.50:   2.687 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   14.397 ms/op
                 createUser·p0.999:  30.802 ms/op
                 createUser·p0.9999: 31.520 ms/op
                 createUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10387
  mean =      3.081 ±(99.9%) 0.069 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3571 
    [ 2.500,  5.000) = 6475 
    [ 5.000,  7.500) = 174 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.988 ms/op
     p(50.0000) =      2.687 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =     14.397 ms/op
     p(99.9000) =     30.802 ms/op
     p(99.9900) =     31.520 ms/op
     p(99.9990) =     31.523 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


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
# Warmup Iteration   1: 3.272 ±(99.9%) 0.109 ms/op
Iteration   1: 1.985 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   1.937 ms/op
                 existUser·p0.90:   2.511 ms/op
                 existUser·p0.95:   2.707 ms/op
                 existUser·p0.99:   4.156 ms/op
                 existUser·p0.999:  5.258 ms/op
                 existUser·p0.9999: 6.465 ms/op
                 existUser·p1.00:   6.570 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16111
  mean =      1.985 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 69 
    [1.000, 1.500) = 2200 
    [1.500, 2.000) = 6561 
    [2.000, 2.500) = 5573 
    [2.500, 3.000) = 1384 
    [3.000, 3.500) = 93 
    [3.500, 4.000) = 66 
    [4.000, 4.500) = 36 
    [4.500, 5.000) = 64 
    [5.000, 5.500) = 54 
    [5.500, 6.000) = 5 
    [6.000, 6.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      1.937 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      4.156 ms/op
     p(99.9000) =      5.258 ms/op
     p(99.9900) =      6.465 ms/op
     p(99.9990) =      6.570 ms/op
     p(99.9999) =      6.570 ms/op
    p(100.0000) =      6.570 ms/op


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
# Warmup Iteration   1: 4.678 ±(99.9%) 0.180 ms/op
Iteration   1: 2.892 ±(99.9%) 0.047 ms/op
                 getUser·p0.00:   0.882 ms/op
                 getUser·p0.50:   2.863 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   5.036 ms/op
                 getUser·p0.999:  27.687 ms/op
                 getUser·p0.9999: 28.735 ms/op
                 getUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11065
  mean =      2.892 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3437 
    [ 2.500,  5.000) = 7517 
    [ 5.000,  7.500) = 78 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      5.036 ms/op
     p(99.9000) =     27.687 ms/op
     p(99.9900) =     28.735 ms/op
     p(99.9990) =     28.770 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


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
# Warmup Iteration   1: 11.256 ±(99.9%) 0.291 ms/op
Iteration   1: 8.255 ±(99.9%) 0.127 ms/op
                 listUser·p0.00:   2.957 ms/op
                 listUser·p0.50:   7.766 ms/op
                 listUser·p0.90:   11.026 ms/op
                 listUser·p0.95:   12.337 ms/op
                 listUser·p0.99:   17.826 ms/op
                 listUser·p0.999:  22.864 ms/op
                 listUser·p0.9999: 24.740 ms/op
                 listUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3893
  mean =      8.255 ±(99.9%) 0.127 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 93 
    [ 5.000,  7.500) = 1577 
    [ 7.500, 10.000) = 1549 
    [10.000, 12.500) = 496 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.957 ms/op
     p(50.0000) =      7.766 ms/op
     p(90.0000) =     11.026 ms/op
     p(95.0000) =     12.337 ms/op
     p(99.0000) =     17.826 ms/op
     p(99.9000) =     22.864 ms/op
     p(99.9900) =     24.740 ms/op
     p(99.9990) =     24.740 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.090          ops/ms
Client.existUser                       thrpt         12.029          ops/ms
Client.getUser                         thrpt          9.456          ops/ms
Client.listUser                        thrpt          3.222          ops/ms
Client.createUser                       avgt          3.173           ms/op
Client.existUser                        avgt          1.792           ms/op
Client.getUser                          avgt          3.282           ms/op
Client.listUser                         avgt          8.507           ms/op
Client.createUser                     sample  10387   3.081 ± 0.069   ms/op
Client.createUser:createUser·p0.00    sample          0.988           ms/op
Client.createUser:createUser·p0.50    sample          2.687           ms/op
Client.createUser:createUser·p0.90    sample          3.826           ms/op
Client.createUser:createUser·p0.95    sample          4.342           ms/op
Client.createUser:createUser·p0.99    sample         14.397           ms/op
Client.createUser:createUser·p0.999   sample         30.802           ms/op
Client.createUser:createUser·p0.9999  sample         31.520           ms/op
Client.createUser:createUser·p1.00    sample         31.523           ms/op
Client.existUser                      sample  16111   1.985 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.713           ms/op
Client.existUser:existUser·p0.50      sample          1.937           ms/op
Client.existUser:existUser·p0.90      sample          2.511           ms/op
Client.existUser:existUser·p0.95      sample          2.707           ms/op
Client.existUser:existUser·p0.99      sample          4.156           ms/op
Client.existUser:existUser·p0.999     sample          5.258           ms/op
Client.existUser:existUser·p0.9999    sample          6.465           ms/op
Client.existUser:existUser·p1.00      sample          6.570           ms/op
Client.getUser                        sample  11065   2.892 ± 0.047   ms/op
Client.getUser:getUser·p0.00          sample          0.882           ms/op
Client.getUser:getUser·p0.50          sample          2.863           ms/op
Client.getUser:getUser·p0.90          sample          3.650           ms/op
Client.getUser:getUser·p0.95          sample          3.850           ms/op
Client.getUser:getUser·p0.99          sample          5.036           ms/op
Client.getUser:getUser·p0.999         sample         27.687           ms/op
Client.getUser:getUser·p0.9999        sample         28.735           ms/op
Client.getUser:getUser·p1.00          sample         28.770           ms/op
Client.listUser                       sample   3893   8.255 ± 0.127   ms/op
Client.listUser:listUser·p0.00        sample          2.957           ms/op
Client.listUser:listUser·p0.50        sample          7.766           ms/op
Client.listUser:listUser·p0.90        sample         11.026           ms/op
Client.listUser:listUser·p0.95        sample         12.337           ms/op
Client.listUser:listUser·p0.99        sample         17.826           ms/op
Client.listUser:listUser·p0.999       sample         22.864           ms/op
Client.listUser:listUser·p0.9999      sample         24.740           ms/op
Client.listUser:listUser·p1.00        sample         24.740           ms/op
