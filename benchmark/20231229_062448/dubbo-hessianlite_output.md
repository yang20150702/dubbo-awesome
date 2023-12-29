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
# Warmup Iteration   1: 2.344 ops/ms
Iteration   1: 6.172 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.172 ops/ms


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
# Warmup Iteration   1: 5.857 ops/ms
Iteration   1: 13.395 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.395 ops/ms


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
# Warmup Iteration   1: 4.071 ops/ms
Iteration   1: 8.361 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.361 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.254 ops/ms
Iteration   1: 3.668 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.668 ops/ms


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
# Warmup Iteration   1: 5.671 ±(99.9%) 0.086 ms/op
Iteration   1: 3.213 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.213 ms/op


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
# Warmup Iteration   1: 3.000 ±(99.9%) 0.036 ms/op
Iteration   1: 1.934 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.934 ms/op


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
# Warmup Iteration   1: 5.180 ±(99.9%) 0.058 ms/op
Iteration   1: 3.367 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.367 ms/op


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
# Warmup Iteration   1: 13.342 ±(99.9%) 0.331 ms/op
Iteration   1: 8.614 ±(99.9%) 0.134 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.614 ms/op


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
# Warmup Iteration   1: 5.120 ±(99.9%) 0.117 ms/op
Iteration   1: 3.065 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   1.108 ms/op
                 createUser·p0.50:   2.785 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   9.880 ms/op
                 createUser·p0.999:  15.712 ms/op
                 createUser·p0.9999: 15.729 ms/op
                 createUser·p1.00:   15.729 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10494
  mean =      3.065 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 2563 
    [ 2.500,  3.750) = 6576 
    [ 3.750,  5.000) = 1063 
    [ 5.000,  6.250) = 85 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      2.785 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      9.880 ms/op
     p(99.9000) =     15.712 ms/op
     p(99.9900) =     15.729 ms/op
     p(99.9990) =     15.729 ms/op
     p(99.9999) =     15.729 ms/op
    p(100.0000) =     15.729 ms/op


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
# Warmup Iteration   1: 3.250 ±(99.9%) 0.091 ms/op
Iteration   1: 1.874 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.482 ms/op
                 existUser·p0.50:   1.784 ms/op
                 existUser·p0.90:   2.347 ms/op
                 existUser·p0.95:   2.519 ms/op
                 existUser·p0.99:   3.256 ms/op
                 existUser·p0.999:  26.903 ms/op
                 existUser·p0.9999: 27.390 ms/op
                 existUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17051
  mean =      1.874 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16148 
    [ 2.500,  5.000) = 861 
    [ 5.000,  7.500) = 9 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      1.784 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.519 ms/op
     p(99.0000) =      3.256 ms/op
     p(99.9000) =     26.903 ms/op
     p(99.9900) =     27.390 ms/op
     p(99.9990) =     27.460 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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
# Warmup Iteration   1: 4.596 ±(99.9%) 0.104 ms/op
Iteration   1: 2.817 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.703 ms/op
                 getUser·p0.50:   2.703 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   5.807 ms/op
                 getUser·p0.999:  7.029 ms/op
                 getUser·p0.9999: 8.300 ms/op
                 getUser·p1.00:   8.380 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11404
  mean =      2.817 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 4 
    [1.000, 1.500) = 71 
    [1.500, 2.000) = 524 
    [2.000, 2.500) = 3477 
    [2.500, 3.000) = 3688 
    [3.000, 3.500) = 2265 
    [3.500, 4.000) = 884 
    [4.000, 4.500) = 290 
    [4.500, 5.000) = 27 
    [5.000, 5.500) = 42 
    [5.500, 6.000) = 32 
    [6.000, 6.500) = 86 
    [6.500, 7.000) = 3 
    [7.000, 7.500) = 6 
    [7.500, 8.000) = 4 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      2.703 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.807 ms/op
     p(99.9000) =      7.029 ms/op
     p(99.9900) =      8.300 ms/op
     p(99.9990) =      8.380 ms/op
     p(99.9999) =      8.380 ms/op
    p(100.0000) =      8.380 ms/op


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
# Warmup Iteration   1: 13.073 ±(99.9%) 0.525 ms/op
Iteration   1: 9.021 ±(99.9%) 0.149 ms/op
                 listUser·p0.00:   2.650 ms/op
                 listUser·p0.50:   8.651 ms/op
                 listUser·p0.90:   12.108 ms/op
                 listUser·p0.95:   13.698 ms/op
                 listUser·p0.99:   20.713 ms/op
                 listUser·p0.999:  24.605 ms/op
                 listUser·p0.9999: 28.082 ms/op
                 listUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3558
  mean =      9.021 ±(99.9%) 0.149 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 96 
    [ 5.000,  7.500) = 883 
    [ 7.500, 10.000) = 1583 
    [10.000, 12.500) = 689 
    [12.500, 15.000) = 221 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.650 ms/op
     p(50.0000) =      8.651 ms/op
     p(90.0000) =     12.108 ms/op
     p(95.0000) =     13.698 ms/op
     p(99.0000) =     20.713 ms/op
     p(99.9000) =     24.605 ms/op
     p(99.9900) =     28.082 ms/op
     p(99.9990) =     28.082 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.172          ops/ms
Client.existUser                       thrpt         13.395          ops/ms
Client.getUser                         thrpt          8.361          ops/ms
Client.listUser                        thrpt          3.668          ops/ms
Client.createUser                       avgt          3.213           ms/op
Client.existUser                        avgt          1.934           ms/op
Client.getUser                          avgt          3.367           ms/op
Client.listUser                         avgt          8.614           ms/op
Client.createUser                     sample  10494   3.065 ± 0.040   ms/op
Client.createUser:createUser·p0.00    sample          1.108           ms/op
Client.createUser:createUser·p0.50    sample          2.785           ms/op
Client.createUser:createUser·p0.90    sample          3.985           ms/op
Client.createUser:createUser·p0.95    sample          4.317           ms/op
Client.createUser:createUser·p0.99    sample          9.880           ms/op
Client.createUser:createUser·p0.999   sample         15.712           ms/op
Client.createUser:createUser·p0.9999  sample         15.729           ms/op
Client.createUser:createUser·p1.00    sample         15.729           ms/op
Client.existUser                      sample  17051   1.874 ± 0.030   ms/op
Client.existUser:existUser·p0.00      sample          0.482           ms/op
Client.existUser:existUser·p0.50      sample          1.784           ms/op
Client.existUser:existUser·p0.90      sample          2.347           ms/op
Client.existUser:existUser·p0.95      sample          2.519           ms/op
Client.existUser:existUser·p0.99      sample          3.256           ms/op
Client.existUser:existUser·p0.999     sample         26.903           ms/op
Client.existUser:existUser·p0.9999    sample         27.390           ms/op
Client.existUser:existUser·p1.00      sample         27.460           ms/op
Client.getUser                        sample  11404   2.817 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          0.703           ms/op
Client.getUser:getUser·p0.50          sample          2.703           ms/op
Client.getUser:getUser·p0.90          sample          3.576           ms/op
Client.getUser:getUser·p0.95          sample          3.932           ms/op
Client.getUser:getUser·p0.99          sample          5.807           ms/op
Client.getUser:getUser·p0.999         sample          7.029           ms/op
Client.getUser:getUser·p0.9999        sample          8.300           ms/op
Client.getUser:getUser·p1.00          sample          8.380           ms/op
Client.listUser                       sample   3558   9.021 ± 0.149   ms/op
Client.listUser:listUser·p0.00        sample          2.650           ms/op
Client.listUser:listUser·p0.50        sample          8.651           ms/op
Client.listUser:listUser·p0.90        sample         12.108           ms/op
Client.listUser:listUser·p0.95        sample         13.698           ms/op
Client.listUser:listUser·p0.99        sample         20.713           ms/op
Client.listUser:listUser·p0.999       sample         24.605           ms/op
Client.listUser:listUser·p0.9999      sample         28.082           ms/op
Client.listUser:listUser·p1.00        sample         28.082           ms/op
