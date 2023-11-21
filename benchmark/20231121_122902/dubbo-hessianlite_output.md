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
# Warmup Iteration   1: 2.493 ops/ms
Iteration   1: 6.538 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.538 ops/ms


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
# Warmup Iteration   1: 6.415 ops/ms
Iteration   1: 11.988 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.988 ops/ms


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
# Warmup Iteration   1: 4.643 ops/ms
Iteration   1: 9.590 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.590 ops/ms


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
# Warmup Iteration   1: 2.228 ops/ms
Iteration   1: 3.695 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.695 ops/ms


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
# Warmup Iteration   1: 5.592 ±(99.9%) 0.101 ms/op
Iteration   1: 3.130 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.130 ms/op


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
# Warmup Iteration   1: 3.247 ±(99.9%) 0.040 ms/op
Iteration   1: 1.966 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.966 ms/op


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
# Warmup Iteration   1: 4.994 ±(99.9%) 0.058 ms/op
Iteration   1: 3.340 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.340 ms/op


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
# Warmup Iteration   1: 10.943 ±(99.9%) 0.290 ms/op
Iteration   1: 7.966 ±(99.9%) 0.066 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.966 ms/op


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
# Warmup Iteration   1: 4.637 ±(99.9%) 0.079 ms/op
Iteration   1: 2.729 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   1.243 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.399 ms/op
                 createUser·p0.95:   3.862 ms/op
                 createUser·p0.99:   4.741 ms/op
                 createUser·p0.999:  15.565 ms/op
                 createUser·p0.9999: 16.684 ms/op
                 createUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11721
  mean =      2.729 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 5136 
    [ 2.500,  3.750) = 5923 
    [ 3.750,  5.000) = 569 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.399 ms/op
     p(95.0000) =      3.862 ms/op
     p(99.0000) =      4.741 ms/op
     p(99.9000) =     15.565 ms/op
     p(99.9900) =     16.684 ms/op
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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.852 ±(99.9%) 0.053 ms/op
Iteration   1: 2.012 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.587 ms/op
                 existUser·p0.50:   1.864 ms/op
                 existUser·p0.90:   2.519 ms/op
                 existUser·p0.95:   2.695 ms/op
                 existUser·p0.99:   3.761 ms/op
                 existUser·p0.999:  15.026 ms/op
                 existUser·p0.9999: 15.336 ms/op
                 existUser·p1.00:   15.385 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15882
  mean =      2.012 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 130 
    [ 1.250,  2.500) = 14087 
    [ 2.500,  3.750) = 1505 
    [ 3.750,  5.000) = 95 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      1.864 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      3.761 ms/op
     p(99.9000) =     15.026 ms/op
     p(99.9900) =     15.336 ms/op
     p(99.9990) =     15.385 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


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
# Warmup Iteration   1: 4.190 ±(99.9%) 0.077 ms/op
Iteration   1: 2.936 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.571 ms/op
                 getUser·p0.50:   2.884 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  10.668 ms/op
                 getUser·p0.9999: 10.959 ms/op
                 getUser·p1.00:   10.961 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10900
  mean =      2.936 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 3192 
    [ 2.500,  3.750) = 6722 
    [ 3.750,  5.000) = 794 
    [ 5.000,  6.250) = 61 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     10.668 ms/op
     p(99.9900) =     10.959 ms/op
     p(99.9990) =     10.961 ms/op
     p(99.9999) =     10.961 ms/op
    p(100.0000) =     10.961 ms/op


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
# Warmup Iteration   1: 11.278 ±(99.9%) 0.383 ms/op
Iteration   1: 8.100 ±(99.9%) 0.125 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   7.717 ms/op
                 listUser·p0.90:   11.272 ms/op
                 listUser·p0.95:   12.480 ms/op
                 listUser·p0.99:   14.738 ms/op
                 listUser·p0.999:  22.975 ms/op
                 listUser·p0.9999: 28.377 ms/op
                 listUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3945
  mean =      8.100 ±(99.9%) 0.125 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 232 
    [ 5.000,  7.500) = 1551 
    [ 7.500, 10.000) = 1386 
    [10.000, 12.500) = 579 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.265 ms/op
     p(50.0000) =      7.717 ms/op
     p(90.0000) =     11.272 ms/op
     p(95.0000) =     12.480 ms/op
     p(99.0000) =     14.738 ms/op
     p(99.9000) =     22.975 ms/op
     p(99.9900) =     28.377 ms/op
     p(99.9990) =     28.377 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.538          ops/ms
Client.existUser                       thrpt         11.988          ops/ms
Client.getUser                         thrpt          9.590          ops/ms
Client.listUser                        thrpt          3.695          ops/ms
Client.createUser                       avgt          3.130           ms/op
Client.existUser                        avgt          1.966           ms/op
Client.getUser                          avgt          3.340           ms/op
Client.listUser                         avgt          7.966           ms/op
Client.createUser                     sample  11721   2.729 ± 0.027   ms/op
Client.createUser:createUser·p0.00    sample          1.243           ms/op
Client.createUser:createUser·p0.50    sample          2.589           ms/op
Client.createUser:createUser·p0.90    sample          3.399           ms/op
Client.createUser:createUser·p0.95    sample          3.862           ms/op
Client.createUser:createUser·p0.99    sample          4.741           ms/op
Client.createUser:createUser·p0.999   sample         15.565           ms/op
Client.createUser:createUser·p0.9999  sample         16.684           ms/op
Client.createUser:createUser·p1.00    sample         16.876           ms/op
Client.existUser                      sample  15882   2.012 ± 0.019   ms/op
Client.existUser:existUser·p0.00      sample          0.587           ms/op
Client.existUser:existUser·p0.50      sample          1.864           ms/op
Client.existUser:existUser·p0.90      sample          2.519           ms/op
Client.existUser:existUser·p0.95      sample          2.695           ms/op
Client.existUser:existUser·p0.99      sample          3.761           ms/op
Client.existUser:existUser·p0.999     sample         15.026           ms/op
Client.existUser:existUser·p0.9999    sample         15.336           ms/op
Client.existUser:existUser·p1.00      sample         15.385           ms/op
Client.getUser                        sample  10900   2.936 ± 0.028   ms/op
Client.getUser:getUser·p0.00          sample          0.571           ms/op
Client.getUser:getUser·p0.50          sample          2.884           ms/op
Client.getUser:getUser·p0.90          sample          3.690           ms/op
Client.getUser:getUser·p0.95          sample          3.965           ms/op
Client.getUser:getUser·p0.99          sample          5.513           ms/op
Client.getUser:getUser·p0.999         sample         10.668           ms/op
Client.getUser:getUser·p0.9999        sample         10.959           ms/op
Client.getUser:getUser·p1.00          sample         10.961           ms/op
Client.listUser                       sample   3945   8.100 ± 0.125   ms/op
Client.listUser:listUser·p0.00        sample          2.265           ms/op
Client.listUser:listUser·p0.50        sample          7.717           ms/op
Client.listUser:listUser·p0.90        sample         11.272           ms/op
Client.listUser:listUser·p0.95        sample         12.480           ms/op
Client.listUser:listUser·p0.99        sample         14.738           ms/op
Client.listUser:listUser·p0.999       sample         22.975           ms/op
Client.listUser:listUser·p0.9999      sample         28.377           ms/op
Client.listUser:listUser·p1.00        sample         28.377           ms/op
