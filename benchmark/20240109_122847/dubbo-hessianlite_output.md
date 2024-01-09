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
# Warmup Iteration   1: 2.139 ops/ms
Iteration   1: 5.619 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.619 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.107 ops/ms
Iteration   1: 11.499 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.499 ops/ms


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
# Warmup Iteration   1: 3.807 ops/ms
Iteration   1: 7.905 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.905 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.187 ops/ms
Iteration   1: 3.352 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.352 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.618 ±(99.9%) 0.078 ms/op
Iteration   1: 3.305 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.305 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.221 ±(99.9%) 0.037 ms/op
Iteration   1: 2.057 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.057 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 5.039 ±(99.9%) 0.051 ms/op
Iteration   1: 3.058 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.058 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.773 ±(99.9%) 0.295 ms/op
Iteration   1: 8.140 ±(99.9%) 0.084 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.140 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.466 ±(99.9%) 0.122 ms/op
Iteration   1: 3.234 ±(99.9%) 0.097 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   2.798 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   7.259 ms/op
                 createUser·p0.999:  40.458 ms/op
                 createUser·p0.9999: 44.040 ms/op
                 createUser·p1.00:   44.040 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9887
  mean =      3.234 ±(99.9%) 0.097 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9491 
    [ 5.000, 10.000) = 332 
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 8 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.033 ms/op
     p(50.0000) =      2.798 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.259 ms/op
     p(99.9000) =     40.458 ms/op
     p(99.9900) =     44.040 ms/op
     p(99.9990) =     44.040 ms/op
     p(99.9999) =     44.040 ms/op
    p(100.0000) =     44.040 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.201 ±(99.9%) 0.072 ms/op
Iteration   1: 2.305 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.440 ms/op
                 existUser·p0.50:   2.302 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.867 ms/op
                 existUser·p0.999:  5.817 ms/op
                 existUser·p0.9999: 6.829 ms/op
                 existUser·p1.00:   7.373 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 13857
  mean =      2.305 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 4 
    [0.500, 1.000) = 32 
    [1.000, 1.500) = 596 
    [1.500, 2.000) = 3976 
    [2.000, 2.500) = 3915 
    [2.500, 3.000) = 4170 
    [3.000, 3.500) = 950 
    [3.500, 4.000) = 89 
    [4.000, 4.500) = 21 
    [4.500, 5.000) = 60 
    [5.000, 5.500) = 24 
    [5.500, 6.000) = 19 
    [6.000, 6.500) = 0 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      2.302 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      5.817 ms/op
     p(99.9900) =      6.829 ms/op
     p(99.9990) =      7.373 ms/op
     p(99.9999) =      7.373 ms/op
    p(100.0000) =      7.373 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.410 ±(99.9%) 0.101 ms/op
Iteration   1: 2.995 ±(99.9%) 0.088 ms/op
                 getUser·p0.00:   0.796 ms/op
                 getUser·p0.50:   2.695 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   6.984 ms/op
                 getUser·p0.999:  50.215 ms/op
                 getUser·p0.9999: 54.136 ms/op
                 getUser·p1.00:   54.264 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10779
  mean =      2.995 ±(99.9%) 0.088 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10566 
    [ 5.000, 10.000) = 109 
    [10.000, 15.000) = 28 
    [15.000, 20.000) = 41 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 4 
    [50.000, 55.000) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      2.695 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      6.984 ms/op
     p(99.9000) =     50.215 ms/op
     p(99.9900) =     54.136 ms/op
     p(99.9990) =     54.264 ms/op
     p(99.9999) =     54.264 ms/op
    p(100.0000) =     54.264 ms/op


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
# Warmup Iteration   1: 12.303 ±(99.9%) 0.432 ms/op
Iteration   1: 8.773 ±(99.9%) 0.161 ms/op
                 listUser·p0.00:   2.535 ms/op
                 listUser·p0.50:   8.348 ms/op
                 listUser·p0.90:   11.977 ms/op
                 listUser·p0.95:   13.042 ms/op
                 listUser·p0.99:   18.013 ms/op
                 listUser·p0.999:  32.063 ms/op
                 listUser·p0.9999: 61.932 ms/op
                 listUser·p1.00:   61.932 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3629
  mean =      8.773 ±(99.9%) 0.161 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 126 
    [ 5.000, 10.000) = 2580 
    [10.000, 15.000) = 834 
    [15.000, 20.000) = 68 
    [20.000, 25.000) = 17 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.535 ms/op
     p(50.0000) =      8.348 ms/op
     p(90.0000) =     11.977 ms/op
     p(95.0000) =     13.042 ms/op
     p(99.0000) =     18.013 ms/op
     p(99.9000) =     32.063 ms/op
     p(99.9900) =     61.932 ms/op
     p(99.9990) =     61.932 ms/op
     p(99.9999) =     61.932 ms/op
    p(100.0000) =     61.932 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.619          ops/ms
Client.existUser                       thrpt         11.499          ops/ms
Client.getUser                         thrpt          7.905          ops/ms
Client.listUser                        thrpt          3.352          ops/ms
Client.createUser                       avgt          3.305           ms/op
Client.existUser                        avgt          2.057           ms/op
Client.getUser                          avgt          3.058           ms/op
Client.listUser                         avgt          8.140           ms/op
Client.createUser                     sample   9887   3.234 ± 0.097   ms/op
Client.createUser:createUser·p0.00    sample          1.033           ms/op
Client.createUser:createUser·p0.50    sample          2.798           ms/op
Client.createUser:createUser·p0.90    sample          4.002           ms/op
Client.createUser:createUser·p0.95    sample          4.719           ms/op
Client.createUser:createUser·p0.99    sample          7.259           ms/op
Client.createUser:createUser·p0.999   sample         40.458           ms/op
Client.createUser:createUser·p0.9999  sample         44.040           ms/op
Client.createUser:createUser·p1.00    sample         44.040           ms/op
Client.existUser                      sample  13857   2.305 ± 0.016   ms/op
Client.existUser:existUser·p0.00      sample          0.440           ms/op
Client.existUser:existUser·p0.50      sample          2.302           ms/op
Client.existUser:existUser·p0.90      sample          2.953           ms/op
Client.existUser:existUser·p0.95      sample          3.138           ms/op
Client.existUser:existUser·p0.99      sample          3.867           ms/op
Client.existUser:existUser·p0.999     sample          5.817           ms/op
Client.existUser:existUser·p0.9999    sample          6.829           ms/op
Client.existUser:existUser·p1.00      sample          7.373           ms/op
Client.getUser                        sample  10779   2.995 ± 0.088   ms/op
Client.getUser:getUser·p0.00          sample          0.796           ms/op
Client.getUser:getUser·p0.50          sample          2.695           ms/op
Client.getUser:getUser·p0.90          sample          3.564           ms/op
Client.getUser:getUser·p0.95          sample          3.912           ms/op
Client.getUser:getUser·p0.99          sample          6.984           ms/op
Client.getUser:getUser·p0.999         sample         50.215           ms/op
Client.getUser:getUser·p0.9999        sample         54.136           ms/op
Client.getUser:getUser·p1.00          sample         54.264           ms/op
Client.listUser                       sample   3629   8.773 ± 0.161   ms/op
Client.listUser:listUser·p0.00        sample          2.535           ms/op
Client.listUser:listUser·p0.50        sample          8.348           ms/op
Client.listUser:listUser·p0.90        sample         11.977           ms/op
Client.listUser:listUser·p0.95        sample         13.042           ms/op
Client.listUser:listUser·p0.99        sample         18.013           ms/op
Client.listUser:listUser·p0.999       sample         32.063           ms/op
Client.listUser:listUser·p0.9999      sample         61.932           ms/op
Client.listUser:listUser·p1.00        sample         61.932           ms/op
