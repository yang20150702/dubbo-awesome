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
# Warmup Iteration   1: 2.698 ops/ms
Iteration   1: 5.885 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.885 ops/ms


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
# Warmup Iteration   1: 6.962 ops/ms
Iteration   1: 13.649 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.649 ops/ms


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
# Warmup Iteration   1: 4.939 ops/ms
Iteration   1: 8.311 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.311 ops/ms


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
# Warmup Iteration   1: 2.399 ops/ms
Iteration   1: 3.561 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.561 ops/ms


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
# Warmup Iteration   1: 5.575 ±(99.9%) 0.080 ms/op
Iteration   1: 3.192 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.192 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.231 ±(99.9%) 0.040 ms/op
Iteration   1: 1.968 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.968 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.714 ±(99.9%) 0.073 ms/op
Iteration   1: 3.225 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.225 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.736 ±(99.9%) 0.174 ms/op
Iteration   1: 8.709 ±(99.9%) 0.087 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.709 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.787 ±(99.9%) 0.101 ms/op
Iteration   1: 3.162 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   2.810 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   5.513 ms/op
                 createUser·p0.99:   9.372 ms/op
                 createUser·p0.999:  13.759 ms/op
                 createUser·p0.9999: 14.740 ms/op
                 createUser·p1.00:   14.746 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10204
  mean =      3.162 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 19 
    [ 1.250,  2.500) = 2016 
    [ 2.500,  3.750) = 6743 
    [ 3.750,  5.000) = 840 
    [ 5.000,  6.250) = 182 
    [ 6.250,  7.500) = 165 
    [ 7.500,  8.750) = 94 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      2.810 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      9.372 ms/op
     p(99.9000) =     13.759 ms/op
     p(99.9900) =     14.740 ms/op
     p(99.9990) =     14.746 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


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
# Warmup Iteration   1: 4.077 ±(99.9%) 0.302 ms/op
Iteration   1: 1.903 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.359 ms/op
                 existUser·p0.50:   1.776 ms/op
                 existUser·p0.90:   2.485 ms/op
                 existUser·p0.95:   2.671 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  18.973 ms/op
                 existUser·p0.9999: 19.594 ms/op
                 existUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16803
  mean =      1.903 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 862 
    [ 1.250,  2.500) = 14378 
    [ 2.500,  3.750) = 1401 
    [ 3.750,  5.000) = 20 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.359 ms/op
     p(50.0000) =      1.776 ms/op
     p(90.0000) =      2.485 ms/op
     p(95.0000) =      2.671 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =     18.973 ms/op
     p(99.9900) =     19.594 ms/op
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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.341 ±(99.9%) 0.097 ms/op
Iteration   1: 2.973 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.847 ms/op
                 getUser·p0.50:   2.888 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.104 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  12.373 ms/op
                 getUser·p0.9999: 12.644 ms/op
                 getUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10828
  mean =      2.973 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 20 
    [ 1.250,  2.500) = 2905 
    [ 2.500,  3.750) = 6685 
    [ 3.750,  5.000) = 1043 
    [ 5.000,  6.250) = 74 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     12.373 ms/op
     p(99.9900) =     12.644 ms/op
     p(99.9990) =     12.648 ms/op
     p(99.9999) =     12.648 ms/op
    p(100.0000) =     12.648 ms/op


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
# Warmup Iteration   1: 10.728 ±(99.9%) 0.330 ms/op
Iteration   1: 8.546 ±(99.9%) 0.117 ms/op
                 listUser·p0.00:   3.064 ms/op
                 listUser·p0.50:   8.159 ms/op
                 listUser·p0.90:   11.305 ms/op
                 listUser·p0.95:   12.603 ms/op
                 listUser·p0.99:   15.729 ms/op
                 listUser·p0.999:  20.520 ms/op
                 listUser·p0.9999: 21.594 ms/op
                 listUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3755
  mean =      8.546 ±(99.9%) 0.117 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 87 
    [ 5.000,  7.500) = 1170 
    [ 7.500, 10.000) = 1653 
    [10.000, 12.500) = 644 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.064 ms/op
     p(50.0000) =      8.159 ms/op
     p(90.0000) =     11.305 ms/op
     p(95.0000) =     12.603 ms/op
     p(99.0000) =     15.729 ms/op
     p(99.9000) =     20.520 ms/op
     p(99.9900) =     21.594 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.885          ops/ms
Client.existUser                       thrpt         13.649          ops/ms
Client.getUser                         thrpt          8.311          ops/ms
Client.listUser                        thrpt          3.561          ops/ms
Client.createUser                       avgt          3.192           ms/op
Client.existUser                        avgt          1.968           ms/op
Client.getUser                          avgt          3.225           ms/op
Client.listUser                         avgt          8.709           ms/op
Client.createUser                     sample  10204   3.162 ± 0.044   ms/op
Client.createUser:createUser·p0.00    sample          1.061           ms/op
Client.createUser:createUser·p0.50    sample          2.810           ms/op
Client.createUser:createUser·p0.90    sample          4.121           ms/op
Client.createUser:createUser·p0.95    sample          5.513           ms/op
Client.createUser:createUser·p0.99    sample          9.372           ms/op
Client.createUser:createUser·p0.999   sample         13.759           ms/op
Client.createUser:createUser·p0.9999  sample         14.740           ms/op
Client.createUser:createUser·p1.00    sample         14.746           ms/op
Client.existUser                      sample  16803   1.903 ± 0.027   ms/op
Client.existUser:existUser·p0.00      sample          0.359           ms/op
Client.existUser:existUser·p0.50      sample          1.776           ms/op
Client.existUser:existUser·p0.90      sample          2.485           ms/op
Client.existUser:existUser·p0.95      sample          2.671           ms/op
Client.existUser:existUser·p0.99      sample          3.629           ms/op
Client.existUser:existUser·p0.999     sample         18.973           ms/op
Client.existUser:existUser·p0.9999    sample         19.594           ms/op
Client.existUser:existUser·p1.00      sample         19.661           ms/op
Client.getUser                        sample  10828   2.973 ± 0.028   ms/op
Client.getUser:getUser·p0.00          sample          0.847           ms/op
Client.getUser:getUser·p0.50          sample          2.888           ms/op
Client.getUser:getUser·p0.90          sample          3.817           ms/op
Client.getUser:getUser·p0.95          sample          4.104           ms/op
Client.getUser:getUser·p0.99          sample          6.152           ms/op
Client.getUser:getUser·p0.999         sample         12.373           ms/op
Client.getUser:getUser·p0.9999        sample         12.644           ms/op
Client.getUser:getUser·p1.00          sample         12.648           ms/op
Client.listUser                       sample   3755   8.546 ± 0.117   ms/op
Client.listUser:listUser·p0.00        sample          3.064           ms/op
Client.listUser:listUser·p0.50        sample          8.159           ms/op
Client.listUser:listUser·p0.90        sample         11.305           ms/op
Client.listUser:listUser·p0.95        sample         12.603           ms/op
Client.listUser:listUser·p0.99        sample         15.729           ms/op
Client.listUser:listUser·p0.999       sample         20.520           ms/op
Client.listUser:listUser·p0.9999      sample         21.594           ms/op
Client.listUser:listUser·p1.00        sample         21.594           ms/op
