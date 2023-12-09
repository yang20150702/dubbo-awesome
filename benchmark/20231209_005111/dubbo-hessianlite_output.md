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
# Warmup Iteration   1: 2.496 ops/ms
Iteration   1: 5.921 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.921 ops/ms


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
# Warmup Iteration   1: 5.783 ops/ms
Iteration   1: 12.603 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.603 ops/ms


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
# Warmup Iteration   1: 3.804 ops/ms
Iteration   1: 8.593 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.593 ops/ms


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
# Warmup Iteration   1: 2.301 ops/ms
Iteration   1: 3.384 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.384 ops/ms


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
# Warmup Iteration   1: 5.674 ±(99.9%) 0.083 ms/op
Iteration   1: 3.095 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.095 ms/op


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
# Warmup Iteration   1: 3.777 ±(99.9%) 0.039 ms/op
Iteration   1: 1.876 ±(99.9%) 0.007 ms/op


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
# Warmup Iteration   1: 4.524 ±(99.9%) 0.047 ms/op
Iteration   1: 3.381 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.381 ms/op


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
# Warmup Iteration   1: 12.985 ±(99.9%) 0.310 ms/op
Iteration   1: 10.137 ±(99.9%) 0.180 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  10.137 ms/op


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
# Warmup Iteration   1: 5.109 ±(99.9%) 0.135 ms/op
Iteration   1: 3.239 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   1.241 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   6.171 ms/op
                 createUser·p0.999:  15.165 ms/op
                 createUser·p0.9999: 16.253 ms/op
                 createUser·p1.00:   16.253 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9875
  mean =      3.239 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1028 
    [ 2.500,  3.750) = 7041 
    [ 3.750,  5.000) = 1568 
    [ 5.000,  6.250) = 146 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.171 ms/op
     p(99.9000) =     15.165 ms/op
     p(99.9900) =     16.253 ms/op
     p(99.9990) =     16.253 ms/op
     p(99.9999) =     16.253 ms/op
    p(100.0000) =     16.253 ms/op


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
# Warmup Iteration   1: 3.207 ±(99.9%) 0.078 ms/op
Iteration   1: 1.867 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.403 ms/op
                 existUser·p0.50:   1.782 ms/op
                 existUser·p0.90:   2.134 ms/op
                 existUser·p0.95:   2.301 ms/op
                 existUser·p0.99:   2.868 ms/op
                 existUser·p0.999:  16.801 ms/op
                 existUser·p0.9999: 17.075 ms/op
                 existUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17186
  mean =      1.867 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 16659 
    [ 2.500,  3.750) = 326 
    [ 3.750,  5.000) = 48 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.403 ms/op
     p(50.0000) =      1.782 ms/op
     p(90.0000) =      2.134 ms/op
     p(95.0000) =      2.301 ms/op
     p(99.0000) =      2.868 ms/op
     p(99.9000) =     16.801 ms/op
     p(99.9900) =     17.075 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 4.141 ±(99.9%) 0.104 ms/op
Iteration   1: 3.048 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.991 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   4.891 ms/op
                 getUser·p0.999:  6.202 ms/op
                 getUser·p0.9999: 6.634 ms/op
                 getUser·p1.00:   6.636 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10494
  mean =      3.048 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 23 
    [1.500, 2.000) = 191 
    [2.000, 2.500) = 1846 
    [2.500, 3.000) = 3389 
    [3.000, 3.500) = 2617 
    [3.500, 4.000) = 1747 
    [4.000, 4.500) = 511 
    [4.500, 5.000) = 93 
    [5.000, 5.500) = 43 
    [5.500, 6.000) = 9 
    [6.000, 6.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.991 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      4.891 ms/op
     p(99.9000) =      6.202 ms/op
     p(99.9900) =      6.634 ms/op
     p(99.9990) =      6.636 ms/op
     p(99.9999) =      6.636 ms/op
    p(100.0000) =      6.636 ms/op


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
# Warmup Iteration   1: 13.332 ±(99.9%) 0.575 ms/op
Iteration   1: 8.255 ±(99.9%) 0.133 ms/op
                 listUser·p0.00:   3.187 ms/op
                 listUser·p0.50:   7.750 ms/op
                 listUser·p0.90:   10.797 ms/op
                 listUser·p0.95:   12.304 ms/op
                 listUser·p0.99:   20.021 ms/op
                 listUser·p0.999:  25.660 ms/op
                 listUser·p0.9999: 26.280 ms/op
                 listUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3903
  mean =      8.255 ±(99.9%) 0.133 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 98 
    [ 5.000,  7.500) = 1559 
    [ 7.500, 10.000) = 1652 
    [10.000, 12.500) = 414 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      3.187 ms/op
     p(50.0000) =      7.750 ms/op
     p(90.0000) =     10.797 ms/op
     p(95.0000) =     12.304 ms/op
     p(99.0000) =     20.021 ms/op
     p(99.9000) =     25.660 ms/op
     p(99.9900) =     26.280 ms/op
     p(99.9990) =     26.280 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.921          ops/ms
Client.existUser                       thrpt         12.603          ops/ms
Client.getUser                         thrpt          8.593          ops/ms
Client.listUser                        thrpt          3.384          ops/ms
Client.createUser                       avgt          3.095           ms/op
Client.existUser                        avgt          1.876           ms/op
Client.getUser                          avgt          3.381           ms/op
Client.listUser                         avgt         10.137           ms/op
Client.createUser                     sample   9875   3.239 ± 0.029   ms/op
Client.createUser:createUser·p0.00    sample          1.241           ms/op
Client.createUser:createUser·p0.50    sample          3.047           ms/op
Client.createUser:createUser·p0.90    sample          4.108           ms/op
Client.createUser:createUser·p0.95    sample          4.440           ms/op
Client.createUser:createUser·p0.99    sample          6.171           ms/op
Client.createUser:createUser·p0.999   sample         15.165           ms/op
Client.createUser:createUser·p0.9999  sample         16.253           ms/op
Client.createUser:createUser·p1.00    sample         16.253           ms/op
Client.existUser                      sample  17186   1.867 ± 0.018   ms/op
Client.existUser:existUser·p0.00      sample          0.403           ms/op
Client.existUser:existUser·p0.50      sample          1.782           ms/op
Client.existUser:existUser·p0.90      sample          2.134           ms/op
Client.existUser:existUser·p0.95      sample          2.301           ms/op
Client.existUser:existUser·p0.99      sample          2.868           ms/op
Client.existUser:existUser·p0.999     sample         16.801           ms/op
Client.existUser:existUser·p0.9999    sample         17.075           ms/op
Client.existUser:existUser·p1.00      sample         17.334           ms/op
Client.getUser                        sample  10494   3.048 ± 0.020   ms/op
Client.getUser:getUser·p0.00          sample          0.991           ms/op
Client.getUser:getUser·p0.50          sample          2.966           ms/op
Client.getUser:getUser·p0.90          sample          3.842           ms/op
Client.getUser:getUser·p0.95          sample          4.088           ms/op
Client.getUser:getUser·p0.99          sample          4.891           ms/op
Client.getUser:getUser·p0.999         sample          6.202           ms/op
Client.getUser:getUser·p0.9999        sample          6.634           ms/op
Client.getUser:getUser·p1.00          sample          6.636           ms/op
Client.listUser                       sample   3903   8.255 ± 0.133   ms/op
Client.listUser:listUser·p0.00        sample          3.187           ms/op
Client.listUser:listUser·p0.50        sample          7.750           ms/op
Client.listUser:listUser·p0.90        sample         10.797           ms/op
Client.listUser:listUser·p0.95        sample         12.304           ms/op
Client.listUser:listUser·p0.99        sample         20.021           ms/op
Client.listUser:listUser·p0.999       sample         25.660           ms/op
Client.listUser:listUser·p0.9999      sample         26.280           ms/op
Client.listUser:listUser·p1.00        sample         26.280           ms/op
