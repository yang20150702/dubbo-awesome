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
# Warmup Iteration   1: 1.604 ops/ms
Iteration   1: 3.536 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.536 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.143 ops/ms
Iteration   1: 9.505 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.505 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 2.462 ops/ms
Iteration   1: 4.795 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.795 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.083 ops/ms
Iteration   1: 1.781 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.781 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 10.212 ±(99.9%) 0.176 ms/op
Iteration   1: 6.644 ±(99.9%) 0.146 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.644 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.505 ±(99.9%) 0.056 ms/op
Iteration   1: 2.695 ±(99.9%) 0.101 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.695 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.394 ±(99.9%) 0.183 ms/op
Iteration   1: 4.195 ±(99.9%) 0.039 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.195 ms/op


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
# Warmup Iteration   1: 24.957 ±(99.9%) 0.449 ms/op
Iteration   1: 18.012 ±(99.9%) 0.226 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  18.012 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.838 ±(99.9%) 0.297 ms/op
Iteration   1: 3.655 ±(99.9%) 0.077 ms/op
                 createUser·p0.00:   1.622 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   5.718 ms/op
                 createUser·p0.95:   7.414 ms/op
                 createUser·p0.99:   12.970 ms/op
                 createUser·p0.999:  26.083 ms/op
                 createUser·p0.9999: 26.214 ms/op
                 createUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 8734
  mean =      3.655 ±(99.9%) 0.077 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 164 
    [ 2.500,  5.000) = 7590 
    [ 5.000,  7.500) = 593 
    [ 7.500, 10.000) = 201 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.622 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      5.718 ms/op
     p(95.0000) =      7.414 ms/op
     p(99.0000) =     12.970 ms/op
     p(99.9000) =     26.083 ms/op
     p(99.9900) =     26.214 ms/op
     p(99.9990) =     26.214 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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
# Warmup Iteration   1: 6.460 ±(99.9%) 0.178 ms/op
Iteration   1: 2.439 ±(99.9%) 0.072 ms/op
                 existUser·p0.00:   0.402 ms/op
                 existUser·p0.50:   1.841 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   5.169 ms/op
                 existUser·p0.99:   12.534 ms/op
                 existUser·p0.999:  39.508 ms/op
                 existUser·p0.9999: 41.091 ms/op
                 existUser·p1.00:   41.091 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 13159
  mean =      2.439 ±(99.9%) 0.072 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12423 
    [ 5.000, 10.000) = 559 
    [10.000, 15.000) = 108 
    [15.000, 20.000) = 37 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 28 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.402 ms/op
     p(50.0000) =      1.841 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =     12.534 ms/op
     p(99.9000) =     39.508 ms/op
     p(99.9900) =     41.091 ms/op
     p(99.9990) =     41.091 ms/op
     p(99.9999) =     41.091 ms/op
    p(100.0000) =     41.091 ms/op


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
# Warmup Iteration   1: 9.107 ±(99.9%) 0.325 ms/op
Iteration   1: 4.229 ±(99.9%) 0.084 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   3.461 ms/op
                 getUser·p0.90:   6.185 ms/op
                 getUser·p0.95:   8.667 ms/op
                 getUser·p0.99:   13.508 ms/op
                 getUser·p0.999:  21.856 ms/op
                 getUser·p0.9999: 23.921 ms/op
                 getUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7554
  mean =      4.229 ±(99.9%) 0.084 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 288 
    [ 2.500,  5.000) = 5675 
    [ 5.000,  7.500) = 1081 
    [ 7.500, 10.000) = 304 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      6.185 ms/op
     p(95.0000) =      8.667 ms/op
     p(99.0000) =     13.508 ms/op
     p(99.9000) =     21.856 ms/op
     p(99.9900) =     23.921 ms/op
     p(99.9990) =     23.921 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


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
# Warmup Iteration   1: 23.524 ±(99.9%) 0.893 ms/op
Iteration   1: 18.540 ±(99.9%) 0.445 ms/op
                 listUser·p0.00:   5.407 ms/op
                 listUser·p0.50:   17.727 ms/op
                 listUser·p0.90:   26.182 ms/op
                 listUser·p0.95:   28.639 ms/op
                 listUser·p0.99:   37.657 ms/op
                 listUser·p0.999:  45.433 ms/op
                 listUser·p0.9999: 45.482 ms/op
                 listUser·p1.00:   45.482 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1739
  mean =     18.540 ±(99.9%) 0.445 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 64 
    [10.000, 15.000) = 369 
    [15.000, 20.000) = 733 
    [20.000, 25.000) = 376 
    [25.000, 30.000) = 131 
    [30.000, 35.000) = 41 
    [35.000, 40.000) = 16 
    [40.000, 45.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      5.407 ms/op
     p(50.0000) =     17.727 ms/op
     p(90.0000) =     26.182 ms/op
     p(95.0000) =     28.639 ms/op
     p(99.0000) =     37.657 ms/op
     p(99.9000) =     45.433 ms/op
     p(99.9900) =     45.482 ms/op
     p(99.9990) =     45.482 ms/op
     p(99.9999) =     45.482 ms/op
    p(100.0000) =     45.482 ms/op


# Run complete. Total time: 00:01:31

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          3.536          ops/ms
Client.existUser                       thrpt          9.505          ops/ms
Client.getUser                         thrpt          4.795          ops/ms
Client.listUser                        thrpt          1.781          ops/ms
Client.createUser                       avgt          6.644           ms/op
Client.existUser                        avgt          2.695           ms/op
Client.getUser                          avgt          4.195           ms/op
Client.listUser                         avgt         18.012           ms/op
Client.createUser                     sample   8734   3.655 ± 0.077   ms/op
Client.createUser:createUser·p0.00    sample          1.622           ms/op
Client.createUser:createUser·p0.50    sample          2.978           ms/op
Client.createUser:createUser·p0.90    sample          5.718           ms/op
Client.createUser:createUser·p0.95    sample          7.414           ms/op
Client.createUser:createUser·p0.99    sample         12.970           ms/op
Client.createUser:createUser·p0.999   sample         26.083           ms/op
Client.createUser:createUser·p0.9999  sample         26.214           ms/op
Client.createUser:createUser·p1.00    sample         26.214           ms/op
Client.existUser                      sample  13159   2.439 ± 0.072   ms/op
Client.existUser:existUser·p0.00      sample          0.402           ms/op
Client.existUser:existUser·p0.50      sample          1.841           ms/op
Client.existUser:existUser·p0.90      sample          3.785           ms/op
Client.existUser:existUser·p0.95      sample          5.169           ms/op
Client.existUser:existUser·p0.99      sample         12.534           ms/op
Client.existUser:existUser·p0.999     sample         39.508           ms/op
Client.existUser:existUser·p0.9999    sample         41.091           ms/op
Client.existUser:existUser·p1.00      sample         41.091           ms/op
Client.getUser                        sample   7554   4.229 ± 0.084   ms/op
Client.getUser:getUser·p0.00          sample          0.931           ms/op
Client.getUser:getUser·p0.50          sample          3.461           ms/op
Client.getUser:getUser·p0.90          sample          6.185           ms/op
Client.getUser:getUser·p0.95          sample          8.667           ms/op
Client.getUser:getUser·p0.99          sample         13.508           ms/op
Client.getUser:getUser·p0.999         sample         21.856           ms/op
Client.getUser:getUser·p0.9999        sample         23.921           ms/op
Client.getUser:getUser·p1.00          sample         23.921           ms/op
Client.listUser                       sample   1739  18.540 ± 0.445   ms/op
Client.listUser:listUser·p0.00        sample          5.407           ms/op
Client.listUser:listUser·p0.50        sample         17.727           ms/op
Client.listUser:listUser·p0.90        sample         26.182           ms/op
Client.listUser:listUser·p0.95        sample         28.639           ms/op
Client.listUser:listUser·p0.99        sample         37.657           ms/op
Client.listUser:listUser·p0.999       sample         45.433           ms/op
Client.listUser:listUser·p0.9999      sample         45.482           ms/op
Client.listUser:listUser·p1.00        sample         45.482           ms/op
