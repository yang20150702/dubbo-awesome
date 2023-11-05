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
# Warmup Iteration   1: 2.447 ops/ms
Iteration   1: 5.970 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.970 ops/ms


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
# Warmup Iteration   1: 6.881 ops/ms
Iteration   1: 12.777 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.777 ops/ms


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
# Warmup Iteration   1: 4.780 ops/ms
Iteration   1: 9.105 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.105 ops/ms


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
# Warmup Iteration   1: 2.188 ops/ms
Iteration   1: 3.576 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.576 ops/ms


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
# Warmup Iteration   1: 5.270 ±(99.9%) 0.062 ms/op
Iteration   1: 3.318 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.318 ms/op


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
# Warmup Iteration   1: 3.253 ±(99.9%) 0.034 ms/op
Iteration   1: 1.780 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.780 ms/op


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
# Warmup Iteration   1: 4.633 ±(99.9%) 0.048 ms/op
Iteration   1: 2.832 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.832 ms/op


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
# Warmup Iteration   1: 11.604 ±(99.9%) 0.179 ms/op
Iteration   1: 8.406 ±(99.9%) 0.085 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.406 ms/op


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
# Warmup Iteration   1: 4.728 ±(99.9%) 0.077 ms/op
Iteration   1: 3.114 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.976 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   6.742 ms/op
                 createUser·p0.999:  16.941 ms/op
                 createUser·p0.9999: 16.974 ms/op
                 createUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10248
  mean =      3.114 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 3343 
    [ 2.500,  3.750) = 4955 
    [ 3.750,  5.000) = 1747 
    [ 5.000,  6.250) = 62 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.880 ±(99.9%) 0.048 ms/op
Iteration   1: 1.862 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   1.739 ms/op
                 existUser·p0.90:   2.241 ms/op
                 existUser·p0.95:   2.499 ms/op
                 existUser·p0.99:   3.150 ms/op
                 existUser·p0.999:  19.595 ms/op
                 existUser·p0.9999: 19.857 ms/op
                 existUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17170
  mean =      1.862 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 764 
    [ 1.250,  2.500) = 15557 
    [ 2.500,  3.750) = 719 
    [ 3.750,  5.000) = 17 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      1.739 ms/op
     p(90.0000) =      2.241 ms/op
     p(95.0000) =      2.499 ms/op
     p(99.0000) =      3.150 ms/op
     p(99.9000) =     19.595 ms/op
     p(99.9900) =     19.857 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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
# Warmup Iteration   1: 4.462 ±(99.9%) 0.100 ms/op
Iteration   1: 3.083 ±(99.9%) 0.227 ms/op
                 getUser·p0.00:   0.434 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   6.388 ms/op
                 getUser·p0.999:  130.493 ms/op
                 getUser·p0.9999: 134.147 ms/op
                 getUser·p1.00:   134.218 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10416
  mean =      3.083 ±(99.9%) 0.227 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 10381 
    [ 12.500,  25.000) = 3 
    [ 25.000,  37.500) = 0 
    [ 37.500,  50.000) = 0 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 0 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 32 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.434 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      6.388 ms/op
     p(99.9000) =    130.493 ms/op
     p(99.9900) =    134.147 ms/op
     p(99.9990) =    134.218 ms/op
     p(99.9999) =    134.218 ms/op
    p(100.0000) =    134.218 ms/op


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
# Warmup Iteration   1: 11.780 ±(99.9%) 0.401 ms/op
Iteration   1: 7.552 ±(99.9%) 0.114 ms/op
                 listUser·p0.00:   2.810 ms/op
                 listUser·p0.50:   7.242 ms/op
                 listUser·p0.90:   9.781 ms/op
                 listUser·p0.95:   11.131 ms/op
                 listUser·p0.99:   14.556 ms/op
                 listUser·p0.999:  23.877 ms/op
                 listUser·p0.9999: 25.985 ms/op
                 listUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4231
  mean =      7.552 ±(99.9%) 0.114 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 262 
    [ 5.000,  7.500) = 2131 
    [ 7.500, 10.000) = 1463 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.810 ms/op
     p(50.0000) =      7.242 ms/op
     p(90.0000) =      9.781 ms/op
     p(95.0000) =     11.131 ms/op
     p(99.0000) =     14.556 ms/op
     p(99.9000) =     23.877 ms/op
     p(99.9900) =     25.985 ms/op
     p(99.9990) =     25.985 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt    Score   Error   Units
Client.createUser                      thrpt           5.970          ops/ms
Client.existUser                       thrpt          12.777          ops/ms
Client.getUser                         thrpt           9.105          ops/ms
Client.listUser                        thrpt           3.576          ops/ms
Client.createUser                       avgt           3.318           ms/op
Client.existUser                        avgt           1.780           ms/op
Client.getUser                          avgt           2.832           ms/op
Client.listUser                         avgt           8.406           ms/op
Client.createUser                     sample  10248    3.114 ± 0.040   ms/op
Client.createUser:createUser·p0.00    sample           0.976           ms/op
Client.createUser:createUser·p0.50    sample           2.990           ms/op
Client.createUser:createUser·p0.90    sample           4.071           ms/op
Client.createUser:createUser·p0.95    sample           4.317           ms/op
Client.createUser:createUser·p0.99    sample           6.742           ms/op
Client.createUser:createUser·p0.999   sample          16.941           ms/op
Client.createUser:createUser·p0.9999  sample          16.974           ms/op
Client.createUser:createUser·p1.00    sample          16.974           ms/op
Client.existUser                      sample  17170    1.862 ± 0.028   ms/op
Client.existUser:existUser·p0.00      sample           0.602           ms/op
Client.existUser:existUser·p0.50      sample           1.739           ms/op
Client.existUser:existUser·p0.90      sample           2.241           ms/op
Client.existUser:existUser·p0.95      sample           2.499           ms/op
Client.existUser:existUser·p0.99      sample           3.150           ms/op
Client.existUser:existUser·p0.999     sample          19.595           ms/op
Client.existUser:existUser·p0.9999    sample          19.857           ms/op
Client.existUser:existUser·p1.00      sample          19.857           ms/op
Client.getUser                        sample  10416    3.083 ± 0.227   ms/op
Client.getUser:getUser·p0.00          sample           0.434           ms/op
Client.getUser:getUser·p0.50          sample           2.576           ms/op
Client.getUser:getUser·p0.90          sample           3.396           ms/op
Client.getUser:getUser·p0.95          sample           3.727           ms/op
Client.getUser:getUser·p0.99          sample           6.388           ms/op
Client.getUser:getUser·p0.999         sample         130.493           ms/op
Client.getUser:getUser·p0.9999        sample         134.147           ms/op
Client.getUser:getUser·p1.00          sample         134.218           ms/op
Client.listUser                       sample   4231    7.552 ± 0.114   ms/op
Client.listUser:listUser·p0.00        sample           2.810           ms/op
Client.listUser:listUser·p0.50        sample           7.242           ms/op
Client.listUser:listUser·p0.90        sample           9.781           ms/op
Client.listUser:listUser·p0.95        sample          11.131           ms/op
Client.listUser:listUser·p0.99        sample          14.556           ms/op
Client.listUser:listUser·p0.999       sample          23.877           ms/op
Client.listUser:listUser·p0.9999      sample          25.985           ms/op
Client.listUser:listUser·p1.00        sample          25.985           ms/op
