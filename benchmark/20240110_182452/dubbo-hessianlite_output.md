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
# Warmup Iteration   1: 2.292 ops/ms
Iteration   1: 6.429 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.429 ops/ms


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
# Warmup Iteration   1: 6.236 ops/ms
Iteration   1: 13.486 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.486 ops/ms


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
# Warmup Iteration   1: 4.600 ops/ms
Iteration   1: 8.960 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.960 ops/ms


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
# Warmup Iteration   1: 2.363 ops/ms
Iteration   1: 3.953 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.953 ops/ms


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
# Warmup Iteration   1: 5.010 ±(99.9%) 0.063 ms/op
Iteration   1: 3.060 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.060 ms/op


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
# Warmup Iteration   1: 3.229 ±(99.9%) 0.032 ms/op
Iteration   1: 1.876 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.876 ms/op


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
# Warmup Iteration   1: 4.260 ±(99.9%) 0.055 ms/op
Iteration   1: 2.753 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.753 ms/op


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
# Warmup Iteration   1: 12.354 ±(99.9%) 0.205 ms/op
Iteration   1: 8.082 ±(99.9%) 0.057 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.082 ms/op


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
# Warmup Iteration   1: 4.935 ±(99.9%) 0.108 ms/op
Iteration   1: 3.075 ±(99.9%) 0.056 ms/op
                 createUser·p0.00:   1.411 ms/op
                 createUser·p0.50:   2.871 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   6.012 ms/op
                 createUser·p0.999:  24.478 ms/op
                 createUser·p0.9999: 25.867 ms/op
                 createUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10406
  mean =      3.075 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2349 
    [ 2.500,  5.000) = 7886 
    [ 5.000,  7.500) = 75 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.411 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      6.012 ms/op
     p(99.9000) =     24.478 ms/op
     p(99.9900) =     25.867 ms/op
     p(99.9990) =     25.887 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 2.947 ±(99.9%) 0.061 ms/op
Iteration   1: 1.670 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.625 ms/op
                 existUser·p0.50:   1.563 ms/op
                 existUser·p0.90:   2.138 ms/op
                 existUser·p0.95:   2.322 ms/op
                 existUser·p0.99:   3.057 ms/op
                 existUser·p0.999:  5.864 ms/op
                 existUser·p0.9999: 6.508 ms/op
                 existUser·p1.00:   6.545 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19153
  mean =      1.670 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 118 
    [1.000, 1.500) = 7278 
    [1.500, 2.000) = 8812 
    [2.000, 2.500) = 2358 
    [2.500, 3.000) = 371 
    [3.000, 3.500) = 80 
    [3.500, 4.000) = 79 
    [4.000, 4.500) = 4 
    [4.500, 5.000) = 4 
    [5.000, 5.500) = 7 
    [5.500, 6.000) = 35 
    [6.000, 6.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      1.563 ms/op
     p(90.0000) =      2.138 ms/op
     p(95.0000) =      2.322 ms/op
     p(99.0000) =      3.057 ms/op
     p(99.9000) =      5.864 ms/op
     p(99.9900) =      6.508 ms/op
     p(99.9990) =      6.545 ms/op
     p(99.9999) =      6.545 ms/op
    p(100.0000) =      6.545 ms/op


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
# Warmup Iteration   1: 4.441 ±(99.9%) 0.121 ms/op
Iteration   1: 3.204 ±(99.9%) 0.053 ms/op
                 getUser·p0.00:   0.984 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.241 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  29.394 ms/op
                 getUser·p0.9999: 30.999 ms/op
                 getUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9985
  mean =      3.204 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1366 
    [ 2.500,  5.000) = 8411 
    [ 5.000,  7.500) = 173 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.241 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     29.394 ms/op
     p(99.9900) =     30.999 ms/op
     p(99.9990) =     30.999 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


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
# Warmup Iteration   1: 11.256 ±(99.9%) 0.373 ms/op
Iteration   1: 8.328 ±(99.9%) 0.129 ms/op
                 listUser·p0.00:   1.733 ms/op
                 listUser·p0.50:   8.004 ms/op
                 listUser·p0.90:   11.203 ms/op
                 listUser·p0.95:   12.321 ms/op
                 listUser·p0.99:   16.974 ms/op
                 listUser·p0.999:  19.830 ms/op
                 listUser·p0.9999: 21.201 ms/op
                 listUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3891
  mean =      8.328 ±(99.9%) 0.129 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 174 
    [ 5.000,  7.500) = 1409 
    [ 7.500, 10.000) = 1505 
    [10.000, 12.500) = 624 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.733 ms/op
     p(50.0000) =      8.004 ms/op
     p(90.0000) =     11.203 ms/op
     p(95.0000) =     12.321 ms/op
     p(99.0000) =     16.974 ms/op
     p(99.9000) =     19.830 ms/op
     p(99.9900) =     21.201 ms/op
     p(99.9990) =     21.201 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.429          ops/ms
Client.existUser                       thrpt         13.486          ops/ms
Client.getUser                         thrpt          8.960          ops/ms
Client.listUser                        thrpt          3.953          ops/ms
Client.createUser                       avgt          3.060           ms/op
Client.existUser                        avgt          1.876           ms/op
Client.getUser                          avgt          2.753           ms/op
Client.listUser                         avgt          8.082           ms/op
Client.createUser                     sample  10406   3.075 ± 0.056   ms/op
Client.createUser:createUser·p0.00    sample          1.411           ms/op
Client.createUser:createUser·p0.50    sample          2.871           ms/op
Client.createUser:createUser·p0.90    sample          3.650           ms/op
Client.createUser:createUser·p0.95    sample          3.908           ms/op
Client.createUser:createUser·p0.99    sample          6.012           ms/op
Client.createUser:createUser·p0.999   sample         24.478           ms/op
Client.createUser:createUser·p0.9999  sample         25.867           ms/op
Client.createUser:createUser·p1.00    sample         25.887           ms/op
Client.existUser                      sample  19153   1.670 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.625           ms/op
Client.existUser:existUser·p0.50      sample          1.563           ms/op
Client.existUser:existUser·p0.90      sample          2.138           ms/op
Client.existUser:existUser·p0.95      sample          2.322           ms/op
Client.existUser:existUser·p0.99      sample          3.057           ms/op
Client.existUser:existUser·p0.999     sample          5.864           ms/op
Client.existUser:existUser·p0.9999    sample          6.508           ms/op
Client.existUser:existUser·p1.00      sample          6.545           ms/op
Client.getUser                        sample   9985   3.204 ± 0.053   ms/op
Client.getUser:getUser·p0.00          sample          0.984           ms/op
Client.getUser:getUser·p0.50          sample          3.072           ms/op
Client.getUser:getUser·p0.90          sample          3.842           ms/op
Client.getUser:getUser·p0.95          sample          4.241           ms/op
Client.getUser:getUser·p0.99          sample          5.472           ms/op
Client.getUser:getUser·p0.999         sample         29.394           ms/op
Client.getUser:getUser·p0.9999        sample         30.999           ms/op
Client.getUser:getUser·p1.00          sample         30.999           ms/op
Client.listUser                       sample   3891   8.328 ± 0.129   ms/op
Client.listUser:listUser·p0.00        sample          1.733           ms/op
Client.listUser:listUser·p0.50        sample          8.004           ms/op
Client.listUser:listUser·p0.90        sample         11.203           ms/op
Client.listUser:listUser·p0.95        sample         12.321           ms/op
Client.listUser:listUser·p0.99        sample         16.974           ms/op
Client.listUser:listUser·p0.999       sample         19.830           ms/op
Client.listUser:listUser·p0.9999      sample         21.201           ms/op
Client.listUser:listUser·p1.00        sample         21.201           ms/op
