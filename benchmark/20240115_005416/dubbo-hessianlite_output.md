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
# Warmup Iteration   1: 2.036 ops/ms
Iteration   1: 5.872 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.872 ops/ms


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
# Warmup Iteration   1: 6.225 ops/ms
Iteration   1: 12.751 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.751 ops/ms


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
# Warmup Iteration   1: 3.963 ops/ms
Iteration   1: 9.194 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.194 ops/ms


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
# Warmup Iteration   1: 2.134 ops/ms
Iteration   1: 3.546 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.546 ops/ms


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
# Warmup Iteration   1: 5.666 ±(99.9%) 0.074 ms/op
Iteration   1: 3.382 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.382 ms/op


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
# Warmup Iteration   1: 3.558 ±(99.9%) 0.032 ms/op
Iteration   1: 2.089 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.089 ms/op


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
# Warmup Iteration   1: 5.653 ±(99.9%) 0.085 ms/op
Iteration   1: 3.379 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.379 ms/op


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
# Warmup Iteration   1: 13.503 ±(99.9%) 0.309 ms/op
Iteration   1: 8.721 ±(99.9%) 0.092 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.721 ms/op


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
# Warmup Iteration   1: 5.817 ±(99.9%) 0.133 ms/op
Iteration   1: 3.346 ±(99.9%) 0.064 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.503 ms/op
                 createUser·p0.99:   8.815 ms/op
                 createUser·p0.999:  26.804 ms/op
                 createUser·p0.9999: 27.394 ms/op
                 createUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9685
  mean =      3.346 ±(99.9%) 0.064 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 684 
    [ 2.500,  5.000) = 8722 
    [ 5.000,  7.500) = 151 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.503 ms/op
     p(99.0000) =      8.815 ms/op
     p(99.9000) =     26.804 ms/op
     p(99.9900) =     27.394 ms/op
     p(99.9990) =     27.394 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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
# Warmup Iteration   1: 3.103 ±(99.9%) 0.068 ms/op
Iteration   1: 1.972 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.663 ms/op
                 existUser·p0.50:   1.776 ms/op
                 existUser·p0.90:   2.789 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  7.310 ms/op
                 existUser·p0.9999: 9.388 ms/op
                 existUser·p1.00:   9.388 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16295
  mean =      1.972 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 69 
    [ 1.000,  2.000) = 9832 
    [ 2.000,  3.000) = 5406 
    [ 3.000,  4.000) = 795 
    [ 4.000,  5.000) = 97 
    [ 5.000,  6.000) = 62 
    [ 6.000,  7.000) = 12 
    [ 7.000,  8.000) = 13 
    [ 8.000,  9.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      1.776 ms/op
     p(90.0000) =      2.789 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      4.121 ms/op
     p(99.9000) =      7.310 ms/op
     p(99.9900) =      9.388 ms/op
     p(99.9990) =      9.388 ms/op
     p(99.9999) =      9.388 ms/op
    p(100.0000) =      9.388 ms/op


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
# Warmup Iteration   1: 4.568 ±(99.9%) 0.114 ms/op
Iteration   1: 3.426 ±(99.9%) 0.050 ms/op
                 getUser·p0.00:   1.108 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   8.290 ms/op
                 getUser·p0.999:  20.618 ms/op
                 getUser·p0.9999: 21.889 ms/op
                 getUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9466
  mean =      3.426 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1483 
    [ 2.500,  5.000) = 7676 
    [ 5.000,  7.500) = 177 
    [ 7.500, 10.000) = 65 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      8.290 ms/op
     p(99.9000) =     20.618 ms/op
     p(99.9900) =     21.889 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 11.330 ±(99.9%) 0.386 ms/op
Iteration   1: 7.901 ±(99.9%) 0.129 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   7.487 ms/op
                 listUser·p0.90:   10.322 ms/op
                 listUser·p0.95:   12.141 ms/op
                 listUser·p0.99:   19.142 ms/op
                 listUser·p0.999:  26.141 ms/op
                 listUser·p0.9999: 29.065 ms/op
                 listUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4240
  mean =      7.901 ±(99.9%) 0.129 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 206 
    [ 5.000,  7.500) = 1919 
    [ 7.500, 10.000) = 1624 
    [10.000, 12.500) = 308 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.327 ms/op
     p(50.0000) =      7.487 ms/op
     p(90.0000) =     10.322 ms/op
     p(95.0000) =     12.141 ms/op
     p(99.0000) =     19.142 ms/op
     p(99.9000) =     26.141 ms/op
     p(99.9900) =     29.065 ms/op
     p(99.9990) =     29.065 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.872          ops/ms
Client.existUser                       thrpt         12.751          ops/ms
Client.getUser                         thrpt          9.194          ops/ms
Client.listUser                        thrpt          3.546          ops/ms
Client.createUser                       avgt          3.382           ms/op
Client.existUser                        avgt          2.089           ms/op
Client.getUser                          avgt          3.379           ms/op
Client.listUser                         avgt          8.721           ms/op
Client.createUser                     sample   9685   3.346 ± 0.064   ms/op
Client.createUser:createUser·p0.00    sample          1.370           ms/op
Client.createUser:createUser·p0.50    sample          3.002           ms/op
Client.createUser:createUser·p0.90    sample          4.129           ms/op
Client.createUser:createUser·p0.95    sample          4.503           ms/op
Client.createUser:createUser·p0.99    sample          8.815           ms/op
Client.createUser:createUser·p0.999   sample         26.804           ms/op
Client.createUser:createUser·p0.9999  sample         27.394           ms/op
Client.createUser:createUser·p1.00    sample         27.394           ms/op
Client.existUser                      sample  16295   1.972 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample          0.663           ms/op
Client.existUser:existUser·p0.50      sample          1.776           ms/op
Client.existUser:existUser·p0.90      sample          2.789           ms/op
Client.existUser:existUser·p0.95      sample          3.072           ms/op
Client.existUser:existUser·p0.99      sample          4.121           ms/op
Client.existUser:existUser·p0.999     sample          7.310           ms/op
Client.existUser:existUser·p0.9999    sample          9.388           ms/op
Client.existUser:existUser·p1.00      sample          9.388           ms/op
Client.getUser                        sample   9466   3.426 ± 0.050   ms/op
Client.getUser:getUser·p0.00          sample          1.108           ms/op
Client.getUser:getUser·p0.50          sample          3.285           ms/op
Client.getUser:getUser·p0.90          sample          4.440           ms/op
Client.getUser:getUser·p0.95          sample          4.727           ms/op
Client.getUser:getUser·p0.99          sample          8.290           ms/op
Client.getUser:getUser·p0.999         sample         20.618           ms/op
Client.getUser:getUser·p0.9999        sample         21.889           ms/op
Client.getUser:getUser·p1.00          sample         21.889           ms/op
Client.listUser                       sample   4240   7.901 ± 0.129   ms/op
Client.listUser:listUser·p0.00        sample          2.327           ms/op
Client.listUser:listUser·p0.50        sample          7.487           ms/op
Client.listUser:listUser·p0.90        sample         10.322           ms/op
Client.listUser:listUser·p0.95        sample         12.141           ms/op
Client.listUser:listUser·p0.99        sample         19.142           ms/op
Client.listUser:listUser·p0.999       sample         26.141           ms/op
Client.listUser:listUser·p0.9999      sample         29.065           ms/op
Client.listUser:listUser·p1.00        sample         29.065           ms/op
