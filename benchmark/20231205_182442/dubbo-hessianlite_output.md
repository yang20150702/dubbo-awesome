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
# Warmup Iteration   1: 2.459 ops/ms
Iteration   1: 6.751 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.751 ops/ms


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
# Warmup Iteration   1: 6.594 ops/ms
Iteration   1: 13.275 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.275 ops/ms


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
# Warmup Iteration   1: 4.022 ops/ms
Iteration   1: 8.370 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.370 ops/ms


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
# Warmup Iteration   1: 2.120 ops/ms
Iteration   1: 3.507 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.507 ops/ms


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
# Warmup Iteration   1: 5.702 ±(99.9%) 0.092 ms/op
Iteration   1: 3.126 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.126 ms/op


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
# Warmup Iteration   1: 3.531 ±(99.9%) 0.032 ms/op
Iteration   1: 1.878 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.878 ms/op


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
# Warmup Iteration   1: 4.775 ±(99.9%) 0.066 ms/op
Iteration   1: 3.323 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.323 ms/op


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
# Warmup Iteration   1: 12.909 ±(99.9%) 0.260 ms/op
Iteration   1: 8.488 ±(99.9%) 0.075 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.488 ms/op


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
# Warmup Iteration   1: 5.723 ±(99.9%) 0.156 ms/op
Iteration   1: 3.452 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.693 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.785 ms/op
                 createUser·p0.99:   6.011 ms/op
                 createUser·p0.999:  11.567 ms/op
                 createUser·p0.9999: 12.730 ms/op
                 createUser·p1.00:   12.730 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9258
  mean =      3.452 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 1330 
    [ 2.500,  3.750) = 4902 
    [ 3.750,  5.000) = 2732 
    [ 5.000,  6.250) = 216 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.785 ms/op
     p(99.0000) =      6.011 ms/op
     p(99.9000) =     11.567 ms/op
     p(99.9900) =     12.730 ms/op
     p(99.9990) =     12.730 ms/op
     p(99.9999) =     12.730 ms/op
    p(100.0000) =     12.730 ms/op


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
# Warmup Iteration   1: 3.120 ±(99.9%) 0.069 ms/op
Iteration   1: 1.829 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.454 ms/op
                 existUser·p0.50:   1.774 ms/op
                 existUser·p0.90:   2.093 ms/op
                 existUser·p0.95:   2.347 ms/op
                 existUser·p0.99:   3.252 ms/op
                 existUser·p0.999:  6.385 ms/op
                 existUser·p0.9999: 6.616 ms/op
                 existUser·p1.00:   7.004 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17524
  mean =      1.829 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 1 
    [0.500, 1.000) = 76 
    [1.000, 1.500) = 873 
    [1.500, 2.000) = 13847 
    [2.000, 2.500) = 2063 
    [2.500, 3.000) = 439 
    [3.000, 3.500) = 87 
    [3.500, 4.000) = 53 
    [4.000, 4.500) = 5 
    [4.500, 5.000) = 21 
    [5.000, 5.500) = 13 
    [5.500, 6.000) = 1 
    [6.000, 6.500) = 44 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.454 ms/op
     p(50.0000) =      1.774 ms/op
     p(90.0000) =      2.093 ms/op
     p(95.0000) =      2.347 ms/op
     p(99.0000) =      3.252 ms/op
     p(99.9000) =      6.385 ms/op
     p(99.9900) =      6.616 ms/op
     p(99.9990) =      7.004 ms/op
     p(99.9999) =      7.004 ms/op
    p(100.0000) =      7.004 ms/op


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
# Warmup Iteration   1: 4.670 ±(99.9%) 0.121 ms/op
Iteration   1: 2.884 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.637 ms/op
                 getUser·p0.50:   2.753 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   5.088 ms/op
                 getUser·p0.999:  9.031 ms/op
                 getUser·p0.9999: 10.579 ms/op
                 getUser·p1.00:   10.617 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11087
  mean =      2.884 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 308 
    [ 2.000,  3.000) = 6995 
    [ 3.000,  4.000) = 3285 
    [ 4.000,  5.000) = 368 
    [ 5.000,  6.000) = 65 
    [ 6.000,  7.000) = 33 
    [ 7.000,  8.000) = 18 
    [ 8.000,  9.000) = 3 
    [ 9.000, 10.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      2.753 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.088 ms/op
     p(99.9000) =      9.031 ms/op
     p(99.9900) =     10.579 ms/op
     p(99.9990) =     10.617 ms/op
     p(99.9999) =     10.617 ms/op
    p(100.0000) =     10.617 ms/op


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
# Warmup Iteration   1: 12.734 ±(99.9%) 0.470 ms/op
Iteration   1: 8.338 ±(99.9%) 0.172 ms/op
                 listUser·p0.00:   2.605 ms/op
                 listUser·p0.50:   7.733 ms/op
                 listUser·p0.90:   10.863 ms/op
                 listUser·p0.95:   12.304 ms/op
                 listUser·p0.99:   20.185 ms/op
                 listUser·p0.999:  38.386 ms/op
                 listUser·p0.9999: 44.499 ms/op
                 listUser·p1.00:   44.499 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3856
  mean =      8.338 ±(99.9%) 0.172 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 107 
    [ 5.000, 10.000) = 3127 
    [10.000, 15.000) = 525 
    [15.000, 20.000) = 57 
    [20.000, 25.000) = 8 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 18 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.605 ms/op
     p(50.0000) =      7.733 ms/op
     p(90.0000) =     10.863 ms/op
     p(95.0000) =     12.304 ms/op
     p(99.0000) =     20.185 ms/op
     p(99.9000) =     38.386 ms/op
     p(99.9900) =     44.499 ms/op
     p(99.9990) =     44.499 ms/op
     p(99.9999) =     44.499 ms/op
    p(100.0000) =     44.499 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.751          ops/ms
Client.existUser                       thrpt         13.275          ops/ms
Client.getUser                         thrpt          8.370          ops/ms
Client.listUser                        thrpt          3.507          ops/ms
Client.createUser                       avgt          3.126           ms/op
Client.existUser                        avgt          1.878           ms/op
Client.getUser                          avgt          3.323           ms/op
Client.listUser                         avgt          8.488           ms/op
Client.createUser                     sample   9258   3.452 ± 0.034   ms/op
Client.createUser:createUser·p0.00    sample          0.693           ms/op
Client.createUser:createUser·p0.50    sample          3.351           ms/op
Client.createUser:createUser·p0.90    sample          4.522           ms/op
Client.createUser:createUser·p0.95    sample          4.785           ms/op
Client.createUser:createUser·p0.99    sample          6.011           ms/op
Client.createUser:createUser·p0.999   sample         11.567           ms/op
Client.createUser:createUser·p0.9999  sample         12.730           ms/op
Client.createUser:createUser·p1.00    sample         12.730           ms/op
Client.existUser                      sample  17524   1.829 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.454           ms/op
Client.existUser:existUser·p0.50      sample          1.774           ms/op
Client.existUser:existUser·p0.90      sample          2.093           ms/op
Client.existUser:existUser·p0.95      sample          2.347           ms/op
Client.existUser:existUser·p0.99      sample          3.252           ms/op
Client.existUser:existUser·p0.999     sample          6.385           ms/op
Client.existUser:existUser·p0.9999    sample          6.616           ms/op
Client.existUser:existUser·p1.00      sample          7.004           ms/op
Client.getUser                        sample  11087   2.884 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          0.637           ms/op
Client.getUser:getUser·p0.50          sample          2.753           ms/op
Client.getUser:getUser·p0.90          sample          3.617           ms/op
Client.getUser:getUser·p0.95          sample          3.944           ms/op
Client.getUser:getUser·p0.99          sample          5.088           ms/op
Client.getUser:getUser·p0.999         sample          9.031           ms/op
Client.getUser:getUser·p0.9999        sample         10.579           ms/op
Client.getUser:getUser·p1.00          sample         10.617           ms/op
Client.listUser                       sample   3856   8.338 ± 0.172   ms/op
Client.listUser:listUser·p0.00        sample          2.605           ms/op
Client.listUser:listUser·p0.50        sample          7.733           ms/op
Client.listUser:listUser·p0.90        sample         10.863           ms/op
Client.listUser:listUser·p0.95        sample         12.304           ms/op
Client.listUser:listUser·p0.99        sample         20.185           ms/op
Client.listUser:listUser·p0.999       sample         38.386           ms/op
Client.listUser:listUser·p0.9999      sample         44.499           ms/op
Client.listUser:listUser·p1.00        sample         44.499           ms/op
