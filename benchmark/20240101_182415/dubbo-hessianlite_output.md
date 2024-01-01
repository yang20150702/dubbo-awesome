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
# Warmup Iteration   1: 2.488 ops/ms
Iteration   1: 6.290 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.290 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.744 ops/ms
Iteration   1: 10.684 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.684 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.763 ops/ms
Iteration   1: 9.438 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.438 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.877 ops/ms
Iteration   1: 3.340 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.340 ops/ms


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
# Warmup Iteration   1: 5.973 ±(99.9%) 0.098 ms/op
Iteration   1: 2.972 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.972 ms/op


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
# Warmup Iteration   1: 3.005 ±(99.9%) 0.031 ms/op
Iteration   1: 1.942 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.942 ms/op


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
# Warmup Iteration   1: 4.445 ±(99.9%) 0.056 ms/op
Iteration   1: 2.894 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.894 ms/op


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
# Warmup Iteration   1: 12.085 ±(99.9%) 0.162 ms/op
Iteration   1: 8.932 ±(99.9%) 0.105 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.932 ms/op


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
# Warmup Iteration   1: 4.925 ±(99.9%) 0.119 ms/op
Iteration   1: 3.001 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   1.031 ms/op
                 createUser·p0.50:   2.847 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   8.362 ms/op
                 createUser·p0.999:  18.973 ms/op
                 createUser·p0.9999: 19.130 ms/op
                 createUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10629
  mean =      3.001 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 3109 
    [ 2.500,  3.750) = 6276 
    [ 3.750,  5.000) = 1025 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      8.362 ms/op
     p(99.9000) =     18.973 ms/op
     p(99.9900) =     19.130 ms/op
     p(99.9990) =     19.137 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


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
# Warmup Iteration   1: 2.789 ±(99.9%) 0.059 ms/op
Iteration   1: 1.860 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.652 ms/op
                 existUser·p0.50:   1.833 ms/op
                 existUser·p0.90:   2.302 ms/op
                 existUser·p0.95:   2.483 ms/op
                 existUser·p0.99:   3.104 ms/op
                 existUser·p0.999:  5.126 ms/op
                 existUser·p0.9999: 8.813 ms/op
                 existUser·p1.00:   10.977 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17316
  mean =      1.860 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 652 
    [ 1.250,  2.500) = 15858 
    [ 2.500,  3.750) = 743 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      1.833 ms/op
     p(90.0000) =      2.302 ms/op
     p(95.0000) =      2.483 ms/op
     p(99.0000) =      3.104 ms/op
     p(99.9000) =      5.126 ms/op
     p(99.9900) =      8.813 ms/op
     p(99.9990) =     10.977 ms/op
     p(99.9999) =     10.977 ms/op
    p(100.0000) =     10.977 ms/op


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
# Warmup Iteration   1: 4.425 ±(99.9%) 0.105 ms/op
Iteration   1: 3.260 ±(99.9%) 0.041 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   4.019 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   5.943 ms/op
                 getUser·p0.999:  20.486 ms/op
                 getUser·p0.9999: 21.135 ms/op
                 getUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9806
  mean =      3.260 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1696 
    [ 2.500,  5.000) = 7886 
    [ 5.000,  7.500) = 185 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      4.019 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.943 ms/op
     p(99.9000) =     20.486 ms/op
     p(99.9900) =     21.135 ms/op
     p(99.9990) =     21.135 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 12.398 ±(99.9%) 0.374 ms/op
Iteration   1: 8.228 ±(99.9%) 0.133 ms/op
                 listUser·p0.00:   2.126 ms/op
                 listUser·p0.50:   7.901 ms/op
                 listUser·p0.90:   10.566 ms/op
                 listUser·p0.95:   11.755 ms/op
                 listUser·p0.99:   20.725 ms/op
                 listUser·p0.999:  25.859 ms/op
                 listUser·p0.9999: 27.099 ms/op
                 listUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3950
  mean =      8.228 ±(99.9%) 0.133 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 125 
    [ 5.000,  7.500) = 1480 
    [ 7.500, 10.000) = 1813 
    [10.000, 12.500) = 383 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      2.126 ms/op
     p(50.0000) =      7.901 ms/op
     p(90.0000) =     10.566 ms/op
     p(95.0000) =     11.755 ms/op
     p(99.0000) =     20.725 ms/op
     p(99.9000) =     25.859 ms/op
     p(99.9900) =     27.099 ms/op
     p(99.9990) =     27.099 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.290          ops/ms
Client.existUser                       thrpt         10.684          ops/ms
Client.getUser                         thrpt          9.438          ops/ms
Client.listUser                        thrpt          3.340          ops/ms
Client.createUser                       avgt          2.972           ms/op
Client.existUser                        avgt          1.942           ms/op
Client.getUser                          avgt          2.894           ms/op
Client.listUser                         avgt          8.932           ms/op
Client.createUser                     sample  10629   3.001 ± 0.040   ms/op
Client.createUser:createUser·p0.00    sample          1.031           ms/op
Client.createUser:createUser·p0.50    sample          2.847           ms/op
Client.createUser:createUser·p0.90    sample          3.949           ms/op
Client.createUser:createUser·p0.95    sample          4.227           ms/op
Client.createUser:createUser·p0.99    sample          8.362           ms/op
Client.createUser:createUser·p0.999   sample         18.973           ms/op
Client.createUser:createUser·p0.9999  sample         19.130           ms/op
Client.createUser:createUser·p1.00    sample         19.137           ms/op
Client.existUser                      sample  17316   1.860 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.652           ms/op
Client.existUser:existUser·p0.50      sample          1.833           ms/op
Client.existUser:existUser·p0.90      sample          2.302           ms/op
Client.existUser:existUser·p0.95      sample          2.483           ms/op
Client.existUser:existUser·p0.99      sample          3.104           ms/op
Client.existUser:existUser·p0.999     sample          5.126           ms/op
Client.existUser:existUser·p0.9999    sample          8.813           ms/op
Client.existUser:existUser·p1.00      sample         10.977           ms/op
Client.getUser                        sample   9806   3.260 ± 0.041   ms/op
Client.getUser:getUser·p0.00          sample          0.905           ms/op
Client.getUser:getUser·p0.50          sample          3.211           ms/op
Client.getUser:getUser·p0.90          sample          4.019           ms/op
Client.getUser:getUser·p0.95          sample          4.415           ms/op
Client.getUser:getUser·p0.99          sample          5.943           ms/op
Client.getUser:getUser·p0.999         sample         20.486           ms/op
Client.getUser:getUser·p0.9999        sample         21.135           ms/op
Client.getUser:getUser·p1.00          sample         21.135           ms/op
Client.listUser                       sample   3950   8.228 ± 0.133   ms/op
Client.listUser:listUser·p0.00        sample          2.126           ms/op
Client.listUser:listUser·p0.50        sample          7.901           ms/op
Client.listUser:listUser·p0.90        sample         10.566           ms/op
Client.listUser:listUser·p0.95        sample         11.755           ms/op
Client.listUser:listUser·p0.99        sample         20.725           ms/op
Client.listUser:listUser·p0.999       sample         25.859           ms/op
Client.listUser:listUser·p0.9999      sample         27.099           ms/op
Client.listUser:listUser·p1.00        sample         27.099           ms/op
