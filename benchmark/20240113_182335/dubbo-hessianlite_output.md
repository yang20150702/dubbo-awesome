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
# Warmup Iteration   1: 2.268 ops/ms
Iteration   1: 5.536 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.536 ops/ms


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
# Warmup Iteration   1: 7.322 ops/ms
Iteration   1: 11.745 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.745 ops/ms


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
# Warmup Iteration   1: 4.521 ops/ms
Iteration   1: 9.922 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.922 ops/ms


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
# Warmup Iteration   1: 2.148 ops/ms
Iteration   1: 3.724 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.724 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.206 ±(99.9%) 0.056 ms/op
Iteration   1: 3.068 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.068 ms/op


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
# Warmup Iteration   1: 3.189 ±(99.9%) 0.045 ms/op
Iteration   1: 1.732 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.732 ms/op


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
# Warmup Iteration   1: 4.430 ±(99.9%) 0.052 ms/op
Iteration   1: 3.068 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.068 ms/op


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
# Warmup Iteration   1: 13.171 ±(99.9%) 0.260 ms/op
Iteration   1: 9.538 ±(99.9%) 0.208 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.538 ms/op


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
# Warmup Iteration   1: 5.408 ±(99.9%) 0.303 ms/op
Iteration   1: 3.031 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   1.206 ms/op
                 createUser·p0.50:   2.802 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   6.335 ms/op
                 createUser·p0.999:  9.077 ms/op
                 createUser·p0.9999: 9.602 ms/op
                 createUser·p1.00:   9.634 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10673
  mean =      3.031 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 17 
    [ 1.500,  2.000) = 202 
    [ 2.000,  2.500) = 2440 
    [ 2.500,  3.000) = 4016 
    [ 3.000,  3.500) = 1995 
    [ 3.500,  4.000) = 784 
    [ 4.000,  4.500) = 528 
    [ 4.500,  5.000) = 317 
    [ 5.000,  5.500) = 151 
    [ 5.500,  6.000) = 94 
    [ 6.000,  6.500) = 34 
    [ 6.500,  7.000) = 11 
    [ 7.000,  7.500) = 33 
    [ 7.500,  8.000) = 19 
    [ 8.000,  8.500) = 0 
    [ 8.500,  9.000) = 12 
    [ 9.000,  9.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      2.802 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      6.335 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =      9.602 ms/op
     p(99.9990) =      9.634 ms/op
     p(99.9999) =      9.634 ms/op
    p(100.0000) =      9.634 ms/op


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
# Warmup Iteration   1: 2.989 ±(99.9%) 0.067 ms/op
Iteration   1: 1.957 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.521 ms/op
                 existUser·p0.50:   1.872 ms/op
                 existUser·p0.90:   2.474 ms/op
                 existUser·p0.95:   2.706 ms/op
                 existUser·p0.99:   3.208 ms/op
                 existUser·p0.999:  19.530 ms/op
                 existUser·p0.9999: 19.661 ms/op
                 existUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16385
  mean =      1.957 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 729 
    [ 1.250,  2.500) = 14143 
    [ 2.500,  3.750) = 1402 
    [ 3.750,  5.000) = 42 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      1.872 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.706 ms/op
     p(99.0000) =      3.208 ms/op
     p(99.9000) =     19.530 ms/op
     p(99.9900) =     19.661 ms/op
     p(99.9990) =     19.661 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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
# Warmup Iteration   1: 4.181 ±(99.9%) 0.095 ms/op
Iteration   1: 3.431 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.776 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   7.642 ms/op
                 getUser·p0.999:  10.338 ms/op
                 getUser·p0.9999: 10.715 ms/op
                 getUser·p1.00:   10.715 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9355
  mean =      3.431 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 10 
    [ 1.000,  2.000) = 165 
    [ 2.000,  3.000) = 2710 
    [ 3.000,  4.000) = 4699 
    [ 4.000,  5.000) = 1448 
    [ 5.000,  6.000) = 139 
    [ 6.000,  7.000) = 87 
    [ 7.000,  8.000) = 54 
    [ 8.000,  9.000) = 31 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      7.642 ms/op
     p(99.9000) =     10.338 ms/op
     p(99.9900) =     10.715 ms/op
     p(99.9990) =     10.715 ms/op
     p(99.9999) =     10.715 ms/op
    p(100.0000) =     10.715 ms/op


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
# Warmup Iteration   1: 14.427 ±(99.9%) 0.525 ms/op
Iteration   1: 8.555 ±(99.9%) 0.109 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   8.339 ms/op
                 listUser·p0.90:   11.223 ms/op
                 listUser·p0.95:   12.059 ms/op
                 listUser·p0.99:   13.869 ms/op
                 listUser·p0.999:  19.453 ms/op
                 listUser·p0.9999: 21.758 ms/op
                 listUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3729
  mean =      8.555 ±(99.9%) 0.109 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 76 
    [ 5.000,  7.500) = 1077 
    [ 7.500, 10.000) = 1761 
    [10.000, 12.500) = 690 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.171 ms/op
     p(50.0000) =      8.339 ms/op
     p(90.0000) =     11.223 ms/op
     p(95.0000) =     12.059 ms/op
     p(99.0000) =     13.869 ms/op
     p(99.9000) =     19.453 ms/op
     p(99.9900) =     21.758 ms/op
     p(99.9990) =     21.758 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.536          ops/ms
Client.existUser                       thrpt         11.745          ops/ms
Client.getUser                         thrpt          9.922          ops/ms
Client.listUser                        thrpt          3.724          ops/ms
Client.createUser                       avgt          3.068           ms/op
Client.existUser                        avgt          1.732           ms/op
Client.getUser                          avgt          3.068           ms/op
Client.listUser                         avgt          9.538           ms/op
Client.createUser                     sample  10673   3.031 ± 0.028   ms/op
Client.createUser:createUser·p0.00    sample          1.206           ms/op
Client.createUser:createUser·p0.50    sample          2.802           ms/op
Client.createUser:createUser·p0.90    sample          4.121           ms/op
Client.createUser:createUser·p0.95    sample          4.686           ms/op
Client.createUser:createUser·p0.99    sample          6.335           ms/op
Client.createUser:createUser·p0.999   sample          9.077           ms/op
Client.createUser:createUser·p0.9999  sample          9.602           ms/op
Client.createUser:createUser·p1.00    sample          9.634           ms/op
Client.existUser                      sample  16385   1.957 ± 0.026   ms/op
Client.existUser:existUser·p0.00      sample          0.521           ms/op
Client.existUser:existUser·p0.50      sample          1.872           ms/op
Client.existUser:existUser·p0.90      sample          2.474           ms/op
Client.existUser:existUser·p0.95      sample          2.706           ms/op
Client.existUser:existUser·p0.99      sample          3.208           ms/op
Client.existUser:existUser·p0.999     sample         19.530           ms/op
Client.existUser:existUser·p0.9999    sample         19.661           ms/op
Client.existUser:existUser·p1.00      sample         19.661           ms/op
Client.getUser                        sample   9355   3.431 ± 0.031   ms/op
Client.getUser:getUser·p0.00          sample          0.776           ms/op
Client.getUser:getUser·p0.50          sample          3.363           ms/op
Client.getUser:getUser·p0.90          sample          4.317           ms/op
Client.getUser:getUser·p0.95          sample          4.653           ms/op
Client.getUser:getUser·p0.99          sample          7.642           ms/op
Client.getUser:getUser·p0.999         sample         10.338           ms/op
Client.getUser:getUser·p0.9999        sample         10.715           ms/op
Client.getUser:getUser·p1.00          sample         10.715           ms/op
Client.listUser                       sample   3729   8.555 ± 0.109   ms/op
Client.listUser:listUser·p0.00        sample          2.171           ms/op
Client.listUser:listUser·p0.50        sample          8.339           ms/op
Client.listUser:listUser·p0.90        sample         11.223           ms/op
Client.listUser:listUser·p0.95        sample         12.059           ms/op
Client.listUser:listUser·p0.99        sample         13.869           ms/op
Client.listUser:listUser·p0.999       sample         19.453           ms/op
Client.listUser:listUser·p0.9999      sample         21.758           ms/op
Client.listUser:listUser·p1.00        sample         21.758           ms/op
