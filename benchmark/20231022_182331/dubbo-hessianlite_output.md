# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 0.990 ops/ms
Iteration   1: 2.925 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.925 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:27
# Fork: 1 of 1
# Warmup Iteration   1: 2.744 ops/ms
Iteration   1: 6.135 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.135 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 2.186 ops/ms
Iteration   1: 3.551 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.551 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 0.923 ops/ms
Iteration   1: 1.219 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.219 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 11.771 ±(99.9%) 0.267 ms/op
Iteration   1: 6.527 ±(99.9%) 0.052 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.527 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 7.978 ±(99.9%) 0.180 ms/op
Iteration   1: 3.302 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.302 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:47
# Fork: 1 of 1
# Warmup Iteration   1: 15.922 ±(99.9%) 0.299 ms/op
Iteration   1: 6.969 ±(99.9%) 0.058 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.969 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:40
# Fork: 1 of 1
# Warmup Iteration   1: 30.971 ±(99.9%) 0.637 ms/op
Iteration   1: 20.365 ±(99.9%) 0.265 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  20.365 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:32
# Fork: 1 of 1
# Warmup Iteration   1: 11.983 ±(99.9%) 0.406 ms/op
Iteration   1: 4.669 ±(99.9%) 0.117 ms/op
                 createUser·p0.00:   0.602 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   7.529 ms/op
                 createUser·p0.95:   9.404 ms/op
                 createUser·p0.99:   15.737 ms/op
                 createUser·p0.999:  29.884 ms/op
                 createUser·p0.9999: 32.440 ms/op
                 createUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 6848
  mean =      4.669 ±(99.9%) 0.117 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 5583 
    [ 5.000,  7.500) = 556 
    [ 7.500, 10.000) = 395 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      7.529 ms/op
     p(95.0000) =      9.404 ms/op
     p(99.0000) =     15.737 ms/op
     p(99.9000) =     29.884 ms/op
     p(99.9900) =     32.440 ms/op
     p(99.9990) =     32.440 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.919 ±(99.9%) 0.208 ms/op
Iteration   1: 2.988 ±(99.9%) 0.075 ms/op
                 existUser·p0.00:   0.689 ms/op
                 existUser·p0.50:   2.335 ms/op
                 existUser·p0.90:   4.768 ms/op
                 existUser·p0.95:   7.115 ms/op
                 existUser·p0.99:   10.535 ms/op
                 existUser·p0.999:  31.601 ms/op
                 existUser·p0.9999: 31.719 ms/op
                 existUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 10614
  mean =      2.988 ±(99.9%) 0.075 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6581 
    [ 2.500,  5.000) = 3043 
    [ 5.000,  7.500) = 493 
    [ 7.500, 10.000) = 344 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      2.335 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      7.115 ms/op
     p(99.0000) =     10.535 ms/op
     p(99.9000) =     31.601 ms/op
     p(99.9900) =     31.719 ms/op
     p(99.9990) =     31.719 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:16
# Fork: 1 of 1
# Warmup Iteration   1: 10.326 ±(99.9%) 0.346 ms/op
Iteration   1: 4.773 ±(99.9%) 0.124 ms/op
                 getUser·p0.00:   0.553 ms/op
                 getUser·p0.50:   3.973 ms/op
                 getUser·p0.90:   6.267 ms/op
                 getUser·p0.95:   7.476 ms/op
                 getUser·p0.99:   21.396 ms/op
                 getUser·p0.999:  35.179 ms/op
                 getUser·p0.9999: 47.579 ms/op
                 getUser·p1.00:   47.579 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6803
  mean =      4.773 ±(99.9%) 0.124 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 5408 
    [ 5.000, 10.000) = 1176 
    [10.000, 15.000) = 98 
    [15.000, 20.000) = 30 
    [20.000, 25.000) = 55 
    [25.000, 30.000) = 12 
    [30.000, 35.000) = 16 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      6.267 ms/op
     p(95.0000) =      7.476 ms/op
     p(99.0000) =     21.396 ms/op
     p(99.9000) =     35.179 ms/op
     p(99.9900) =     47.579 ms/op
     p(99.9990) =     47.579 ms/op
     p(99.9999) =     47.579 ms/op
    p(100.0000) =     47.579 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:08
# Fork: 1 of 1
# Warmup Iteration   1: 29.468 ±(99.9%) 1.517 ms/op
Iteration   1: 21.686 ±(99.9%) 0.519 ms/op
                 listUser·p0.00:   8.086 ms/op
                 listUser·p0.50:   20.693 ms/op
                 listUser·p0.90:   27.886 ms/op
                 listUser·p0.95:   32.571 ms/op
                 listUser·p0.99:   47.895 ms/op
                 listUser·p0.999:  55.697 ms/op
                 listUser·p0.9999: 56.164 ms/op
                 listUser·p1.00:   56.164 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1508
  mean =     21.686 ±(99.9%) 0.519 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 15 
    [10.000, 15.000) = 82 
    [15.000, 20.000) = 549 
    [20.000, 25.000) = 596 
    [25.000, 30.000) = 158 
    [30.000, 35.000) = 54 
    [35.000, 40.000) = 16 
    [40.000, 45.000) = 16 
    [45.000, 50.000) = 16 
    [50.000, 55.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      8.086 ms/op
     p(50.0000) =     20.693 ms/op
     p(90.0000) =     27.886 ms/op
     p(95.0000) =     32.571 ms/op
     p(99.0000) =     47.895 ms/op
     p(99.9000) =     55.697 ms/op
     p(99.9900) =     56.164 ms/op
     p(99.9990) =     56.164 ms/op
     p(99.9999) =     56.164 ms/op
    p(100.0000) =     56.164 ms/op


# Run complete. Total time: 00:01:37

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          2.925          ops/ms
Client.existUser                       thrpt          6.135          ops/ms
Client.getUser                         thrpt          3.551          ops/ms
Client.listUser                        thrpt          1.219          ops/ms
Client.createUser                       avgt          6.527           ms/op
Client.existUser                        avgt          3.302           ms/op
Client.getUser                          avgt          6.969           ms/op
Client.listUser                         avgt         20.365           ms/op
Client.createUser                     sample   6848   4.669 ± 0.117   ms/op
Client.createUser:createUser·p0.00    sample          0.602           ms/op
Client.createUser:createUser·p0.50    sample          3.731           ms/op
Client.createUser:createUser·p0.90    sample          7.529           ms/op
Client.createUser:createUser·p0.95    sample          9.404           ms/op
Client.createUser:createUser·p0.99    sample         15.737           ms/op
Client.createUser:createUser·p0.999   sample         29.884           ms/op
Client.createUser:createUser·p0.9999  sample         32.440           ms/op
Client.createUser:createUser·p1.00    sample         32.440           ms/op
Client.existUser                      sample  10614   2.988 ± 0.075   ms/op
Client.existUser:existUser·p0.00      sample          0.689           ms/op
Client.existUser:existUser·p0.50      sample          2.335           ms/op
Client.existUser:existUser·p0.90      sample          4.768           ms/op
Client.existUser:existUser·p0.95      sample          7.115           ms/op
Client.existUser:existUser·p0.99      sample         10.535           ms/op
Client.existUser:existUser·p0.999     sample         31.601           ms/op
Client.existUser:existUser·p0.9999    sample         31.719           ms/op
Client.existUser:existUser·p1.00      sample         31.719           ms/op
Client.getUser                        sample   6803   4.773 ± 0.124   ms/op
Client.getUser:getUser·p0.00          sample          0.553           ms/op
Client.getUser:getUser·p0.50          sample          3.973           ms/op
Client.getUser:getUser·p0.90          sample          6.267           ms/op
Client.getUser:getUser·p0.95          sample          7.476           ms/op
Client.getUser:getUser·p0.99          sample         21.396           ms/op
Client.getUser:getUser·p0.999         sample         35.179           ms/op
Client.getUser:getUser·p0.9999        sample         47.579           ms/op
Client.getUser:getUser·p1.00          sample         47.579           ms/op
Client.listUser                       sample   1508  21.686 ± 0.519   ms/op
Client.listUser:listUser·p0.00        sample          8.086           ms/op
Client.listUser:listUser·p0.50        sample         20.693           ms/op
Client.listUser:listUser·p0.90        sample         27.886           ms/op
Client.listUser:listUser·p0.95        sample         32.571           ms/op
Client.listUser:listUser·p0.99        sample         47.895           ms/op
Client.listUser:listUser·p0.999       sample         55.697           ms/op
Client.listUser:listUser·p0.9999      sample         56.164           ms/op
Client.listUser:listUser·p1.00        sample         56.164           ms/op
