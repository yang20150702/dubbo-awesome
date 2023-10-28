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
# Warmup Iteration   1: 1.160 ops/ms
Iteration   1: 3.052 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.052 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:25
# Fork: 1 of 1
# Warmup Iteration   1: 3.408 ops/ms
Iteration   1: 7.727 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.727 ops/ms


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
# Warmup Iteration   1: 2.456 ops/ms
Iteration   1: 5.609 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.609 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 0.882 ops/ms
Iteration   1: 1.592 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.592 ops/ms


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
# Warmup Iteration   1: 12.053 ±(99.9%) 0.226 ms/op
Iteration   1: 5.759 ±(99.9%) 0.043 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.759 ms/op


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
# Warmup Iteration   1: 7.484 ±(99.9%) 0.111 ms/op
Iteration   1: 2.922 ±(99.9%) 0.053 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.922 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.768 ±(99.9%) 0.167 ms/op
Iteration   1: 3.996 ±(99.9%) 0.063 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.996 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:38
# Fork: 1 of 1
# Warmup Iteration   1: 29.399 ±(99.9%) 0.746 ms/op
Iteration   1: 20.801 ±(99.9%) 0.232 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  20.801 ms/op


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
# Warmup Iteration   1: 9.152 ±(99.9%) 0.256 ms/op
Iteration   1: 4.268 ±(99.9%) 0.106 ms/op
                 createUser·p0.00:   1.350 ms/op
                 createUser·p0.50:   3.486 ms/op
                 createUser·p0.90:   6.611 ms/op
                 createUser·p0.95:   9.825 ms/op
                 createUser·p0.99:   17.667 ms/op
                 createUser·p0.999:  28.412 ms/op
                 createUser·p0.9999: 28.705 ms/op
                 createUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 7585
  mean =      4.268 ±(99.9%) 0.106 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1009 
    [ 2.500,  5.000) = 5378 
    [ 5.000,  7.500) = 486 
    [ 7.500, 10.000) = 345 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      6.611 ms/op
     p(95.0000) =      9.825 ms/op
     p(99.0000) =     17.667 ms/op
     p(99.9000) =     28.412 ms/op
     p(99.9900) =     28.705 ms/op
     p(99.9990) =     28.705 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.191 ±(99.9%) 0.212 ms/op
Iteration   1: 2.470 ±(99.9%) 0.043 ms/op
                 existUser·p0.00:   0.564 ms/op
                 existUser·p0.50:   2.130 ms/op
                 existUser·p0.90:   3.076 ms/op
                 existUser·p0.95:   4.278 ms/op
                 existUser·p0.99:   8.167 ms/op
                 existUser·p0.999:  19.176 ms/op
                 existUser·p0.9999: 19.970 ms/op
                 existUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 13195
  mean =      2.470 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10933 
    [ 2.500,  5.000) = 1805 
    [ 5.000,  7.500) = 270 
    [ 7.500, 10.000) = 91 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      2.130 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      4.278 ms/op
     p(99.0000) =      8.167 ms/op
     p(99.9000) =     19.176 ms/op
     p(99.9900) =     19.970 ms/op
     p(99.9990) =     20.054 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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
# Warmup Iteration   1: 11.240 ±(99.9%) 0.318 ms/op
Iteration   1: 4.610 ±(99.9%) 0.099 ms/op
                 getUser·p0.00:   1.448 ms/op
                 getUser·p0.50:   3.809 ms/op
                 getUser·p0.90:   7.463 ms/op
                 getUser·p0.95:   9.126 ms/op
                 getUser·p0.99:   12.997 ms/op
                 getUser·p0.999:  27.943 ms/op
                 getUser·p0.9999: 31.261 ms/op
                 getUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7136
  mean =      4.610 ±(99.9%) 0.099 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 129 
    [ 2.500,  5.000) = 5339 
    [ 5.000,  7.500) = 962 
    [ 7.500, 10.000) = 463 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      7.463 ms/op
     p(95.0000) =      9.126 ms/op
     p(99.0000) =     12.997 ms/op
     p(99.9000) =     27.943 ms/op
     p(99.9900) =     31.261 ms/op
     p(99.9990) =     31.261 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


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
# Warmup Iteration   1: 25.526 ±(99.9%) 0.883 ms/op
Iteration   1: 18.491 ±(99.9%) 0.467 ms/op
                 listUser·p0.00:   5.923 ms/op
                 listUser·p0.50:   17.367 ms/op
                 listUser·p0.90:   24.592 ms/op
                 listUser·p0.95:   29.049 ms/op
                 listUser·p0.99:   41.982 ms/op
                 listUser·p0.999:  53.475 ms/op
                 listUser·p0.9999: 54.329 ms/op
                 listUser·p1.00:   54.329 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1814
  mean =     18.491 ±(99.9%) 0.467 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 44 
    [10.000, 15.000) = 400 
    [15.000, 20.000) = 869 
    [20.000, 25.000) = 337 
    [25.000, 30.000) = 79 
    [30.000, 35.000) = 31 
    [35.000, 40.000) = 24 
    [40.000, 45.000) = 16 
    [45.000, 50.000) = 7 
    [50.000, 55.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      5.923 ms/op
     p(50.0000) =     17.367 ms/op
     p(90.0000) =     24.592 ms/op
     p(95.0000) =     29.049 ms/op
     p(99.0000) =     41.982 ms/op
     p(99.9000) =     53.475 ms/op
     p(99.9900) =     54.329 ms/op
     p(99.9990) =     54.329 ms/op
     p(99.9999) =     54.329 ms/op
    p(100.0000) =     54.329 ms/op


# Run complete. Total time: 00:01:33

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          3.052          ops/ms
Client.existUser                       thrpt          7.727          ops/ms
Client.getUser                         thrpt          5.609          ops/ms
Client.listUser                        thrpt          1.592          ops/ms
Client.createUser                       avgt          5.759           ms/op
Client.existUser                        avgt          2.922           ms/op
Client.getUser                          avgt          3.996           ms/op
Client.listUser                         avgt         20.801           ms/op
Client.createUser                     sample   7585   4.268 ± 0.106   ms/op
Client.createUser:createUser·p0.00    sample          1.350           ms/op
Client.createUser:createUser·p0.50    sample          3.486           ms/op
Client.createUser:createUser·p0.90    sample          6.611           ms/op
Client.createUser:createUser·p0.95    sample          9.825           ms/op
Client.createUser:createUser·p0.99    sample         17.667           ms/op
Client.createUser:createUser·p0.999   sample         28.412           ms/op
Client.createUser:createUser·p0.9999  sample         28.705           ms/op
Client.createUser:createUser·p1.00    sample         28.705           ms/op
Client.existUser                      sample  13195   2.470 ± 0.043   ms/op
Client.existUser:existUser·p0.00      sample          0.564           ms/op
Client.existUser:existUser·p0.50      sample          2.130           ms/op
Client.existUser:existUser·p0.90      sample          3.076           ms/op
Client.existUser:existUser·p0.95      sample          4.278           ms/op
Client.existUser:existUser·p0.99      sample          8.167           ms/op
Client.existUser:existUser·p0.999     sample         19.176           ms/op
Client.existUser:existUser·p0.9999    sample         19.970           ms/op
Client.existUser:existUser·p1.00      sample         20.054           ms/op
Client.getUser                        sample   7136   4.610 ± 0.099   ms/op
Client.getUser:getUser·p0.00          sample          1.448           ms/op
Client.getUser:getUser·p0.50          sample          3.809           ms/op
Client.getUser:getUser·p0.90          sample          7.463           ms/op
Client.getUser:getUser·p0.95          sample          9.126           ms/op
Client.getUser:getUser·p0.99          sample         12.997           ms/op
Client.getUser:getUser·p0.999         sample         27.943           ms/op
Client.getUser:getUser·p0.9999        sample         31.261           ms/op
Client.getUser:getUser·p1.00          sample         31.261           ms/op
Client.listUser                       sample   1814  18.491 ± 0.467   ms/op
Client.listUser:listUser·p0.00        sample          5.923           ms/op
Client.listUser:listUser·p0.50        sample         17.367           ms/op
Client.listUser:listUser·p0.90        sample         24.592           ms/op
Client.listUser:listUser·p0.95        sample         29.049           ms/op
Client.listUser:listUser·p0.99        sample         41.982           ms/op
Client.listUser:listUser·p0.999       sample         53.475           ms/op
Client.listUser:listUser·p0.9999      sample         54.329           ms/op
Client.listUser:listUser·p1.00        sample         54.329           ms/op
