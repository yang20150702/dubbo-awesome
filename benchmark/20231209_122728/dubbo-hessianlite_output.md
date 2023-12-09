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
# Warmup Iteration   1: 2.360 ops/ms
Iteration   1: 5.425 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.425 ops/ms


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
# Warmup Iteration   1: 6.861 ops/ms
Iteration   1: 12.744 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.744 ops/ms


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
# Warmup Iteration   1: 4.120 ops/ms
Iteration   1: 8.835 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.835 ops/ms


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
# Warmup Iteration   1: 2.039 ops/ms
Iteration   1: 3.195 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.195 ops/ms


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
# Warmup Iteration   1: 5.174 ±(99.9%) 0.063 ms/op
Iteration   1: 3.043 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.043 ms/op


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
# Warmup Iteration   1: 3.241 ±(99.9%) 0.033 ms/op
Iteration   1: 1.961 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.961 ms/op


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
# Warmup Iteration   1: 4.651 ±(99.9%) 0.048 ms/op
Iteration   1: 3.422 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.422 ms/op


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
# Warmup Iteration   1: 13.222 ±(99.9%) 0.237 ms/op
Iteration   1: 9.124 ±(99.9%) 0.159 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.124 ms/op


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
# Warmup Iteration   1: 5.010 ±(99.9%) 0.118 ms/op
Iteration   1: 3.170 ±(99.9%) 0.050 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   2.793 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.795 ms/op
                 createUser·p0.99:   10.687 ms/op
                 createUser·p0.999:  15.433 ms/op
                 createUser·p0.9999: 16.875 ms/op
                 createUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10070
  mean =      3.170 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 2658 
    [ 2.500,  3.750) = 5683 
    [ 3.750,  5.000) = 1282 
    [ 5.000,  6.250) = 91 
    [ 6.250,  7.500) = 112 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      2.793 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.795 ms/op
     p(99.0000) =     10.687 ms/op
     p(99.9000) =     15.433 ms/op
     p(99.9900) =     16.875 ms/op
     p(99.9990) =     16.876 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


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
# Warmup Iteration   1: 3.169 ±(99.9%) 0.087 ms/op
Iteration   1: 1.692 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.514 ms/op
                 existUser·p0.50:   1.554 ms/op
                 existUser·p0.90:   2.105 ms/op
                 existUser·p0.95:   2.347 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  17.204 ms/op
                 existUser·p0.9999: 17.302 ms/op
                 existUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18968
  mean =      1.692 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 800 
    [ 1.250,  2.500) = 17433 
    [ 2.500,  3.750) = 571 
    [ 3.750,  5.000) = 78 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.514 ms/op
     p(50.0000) =      1.554 ms/op
     p(90.0000) =      2.105 ms/op
     p(95.0000) =      2.347 ms/op
     p(99.0000) =      3.502 ms/op
     p(99.9000) =     17.204 ms/op
     p(99.9900) =     17.302 ms/op
     p(99.9990) =     17.302 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


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
# Warmup Iteration   1: 4.603 ±(99.9%) 0.109 ms/op
Iteration   1: 3.272 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   1.009 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   4.174 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  8.296 ms/op
                 getUser·p0.9999: 10.158 ms/op
                 getUser·p1.00:   10.158 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9762
  mean =      3.272 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 191 
    [ 2.000,  3.000) = 3623 
    [ 3.000,  4.000) = 4568 
    [ 4.000,  5.000) = 1184 
    [ 5.000,  6.000) = 123 
    [ 6.000,  7.000) = 49 
    [ 7.000,  8.000) = 14 
    [ 8.000,  9.000) = 3 
    [ 9.000, 10.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.009 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =      8.296 ms/op
     p(99.9900) =     10.158 ms/op
     p(99.9990) =     10.158 ms/op
     p(99.9999) =     10.158 ms/op
    p(100.0000) =     10.158 ms/op


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
# Warmup Iteration   1: 12.871 ±(99.9%) 0.471 ms/op
Iteration   1: 7.747 ±(99.9%) 0.089 ms/op
                 listUser·p0.00:   2.617 ms/op
                 listUser·p0.50:   7.528 ms/op
                 listUser·p0.90:   9.978 ms/op
                 listUser·p0.95:   10.945 ms/op
                 listUser·p0.99:   12.829 ms/op
                 listUser·p0.999:  15.548 ms/op
                 listUser·p0.9999: 26.509 ms/op
                 listUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4124
  mean =      7.747 ±(99.9%) 0.089 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 127 
    [ 5.000,  7.500) = 1901 
    [ 7.500, 10.000) = 1694 
    [10.000, 12.500) = 351 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.617 ms/op
     p(50.0000) =      7.528 ms/op
     p(90.0000) =      9.978 ms/op
     p(95.0000) =     10.945 ms/op
     p(99.0000) =     12.829 ms/op
     p(99.9000) =     15.548 ms/op
     p(99.9900) =     26.509 ms/op
     p(99.9990) =     26.509 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.425          ops/ms
Client.existUser                       thrpt         12.744          ops/ms
Client.getUser                         thrpt          8.835          ops/ms
Client.listUser                        thrpt          3.195          ops/ms
Client.createUser                       avgt          3.043           ms/op
Client.existUser                        avgt          1.961           ms/op
Client.getUser                          avgt          3.422           ms/op
Client.listUser                         avgt          9.124           ms/op
Client.createUser                     sample  10070   3.170 ± 0.050   ms/op
Client.createUser:createUser·p0.00    sample          1.135           ms/op
Client.createUser:createUser·p0.50    sample          2.793           ms/op
Client.createUser:createUser·p0.90    sample          4.022           ms/op
Client.createUser:createUser·p0.95    sample          4.795           ms/op
Client.createUser:createUser·p0.99    sample         10.687           ms/op
Client.createUser:createUser·p0.999   sample         15.433           ms/op
Client.createUser:createUser·p0.9999  sample         16.875           ms/op
Client.createUser:createUser·p1.00    sample         16.876           ms/op
Client.existUser                      sample  18968   1.692 ± 0.018   ms/op
Client.existUser:existUser·p0.00      sample          0.514           ms/op
Client.existUser:existUser·p0.50      sample          1.554           ms/op
Client.existUser:existUser·p0.90      sample          2.105           ms/op
Client.existUser:existUser·p0.95      sample          2.347           ms/op
Client.existUser:existUser·p0.99      sample          3.502           ms/op
Client.existUser:existUser·p0.999     sample         17.204           ms/op
Client.existUser:existUser·p0.9999    sample         17.302           ms/op
Client.existUser:existUser·p1.00      sample         17.302           ms/op
Client.getUser                        sample   9762   3.272 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          1.009           ms/op
Client.getUser:getUser·p0.50          sample          3.166           ms/op
Client.getUser:getUser·p0.90          sample          4.174           ms/op
Client.getUser:getUser·p0.95          sample          4.497           ms/op
Client.getUser:getUser·p0.99          sample          5.792           ms/op
Client.getUser:getUser·p0.999         sample          8.296           ms/op
Client.getUser:getUser·p0.9999        sample         10.158           ms/op
Client.getUser:getUser·p1.00          sample         10.158           ms/op
Client.listUser                       sample   4124   7.747 ± 0.089   ms/op
Client.listUser:listUser·p0.00        sample          2.617           ms/op
Client.listUser:listUser·p0.50        sample          7.528           ms/op
Client.listUser:listUser·p0.90        sample          9.978           ms/op
Client.listUser:listUser·p0.95        sample         10.945           ms/op
Client.listUser:listUser·p0.99        sample         12.829           ms/op
Client.listUser:listUser·p0.999       sample         15.548           ms/op
Client.listUser:listUser·p0.9999      sample         26.509           ms/op
Client.listUser:listUser·p1.00        sample         26.509           ms/op
