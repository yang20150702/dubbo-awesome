# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.185 ops/ms
Iteration   1: 2.800 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.800 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 2.982 ops/ms
Iteration   1: 6.379 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.379 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.779 ops/ms
Iteration   1: 5.319 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.319 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.893 ops/ms
Iteration   1: 1.481 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.481 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 16.161 ±(99.9%) 0.213 ms/op
Iteration   1: 6.043 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.043 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.240 ±(99.9%) 0.068 ms/op
Iteration   1: 3.342 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.342 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.053 ±(99.9%) 0.109 ms/op
Iteration   1: 4.345 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.345 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 26.545 ±(99.9%) 0.588 ms/op
Iteration   1: 15.105 ±(99.9%) 0.061 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.105 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.724 ±(99.9%) 0.399 ms/op
Iteration   1: 5.471 ±(99.9%) 0.109 ms/op
                 createUser·p0.00:   1.346 ms/op
                 createUser·p0.50:   4.993 ms/op
                 createUser·p0.90:   8.520 ms/op
                 createUser·p0.95:   11.731 ms/op
                 createUser·p0.99:   14.664 ms/op
                 createUser·p0.999:  17.961 ms/op
                 createUser·p0.9999: 17.990 ms/op
                 createUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5860
  mean =      5.471 ±(99.9%) 0.109 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 155 
    [ 2.500,  3.750) = 902 
    [ 3.750,  5.000) = 1942 
    [ 5.000,  6.250) = 1699 
    [ 6.250,  7.500) = 466 
    [ 7.500,  8.750) = 119 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 144 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 132 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.346 ms/op
     p(50.0000) =      4.993 ms/op
     p(90.0000) =      8.520 ms/op
     p(95.0000) =     11.731 ms/op
     p(99.0000) =     14.664 ms/op
     p(99.9000) =     17.961 ms/op
     p(99.9900) =     17.990 ms/op
     p(99.9990) =     17.990 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.650 ±(99.9%) 0.195 ms/op
Iteration   1: 3.234 ±(99.9%) 0.042 ms/op
                 existUser·p0.00:   0.565 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   6.177 ms/op
                 existUser·p0.999:  20.157 ms/op
                 existUser·p0.9999: 20.644 ms/op
                 existUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9863
  mean =      3.234 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 857 
    [ 2.500,  5.000) = 8877 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     20.157 ms/op
     p(99.9900) =     20.644 ms/op
     p(99.9990) =     20.644 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 8.488 ±(99.9%) 0.274 ms/op
Iteration   1: 4.062 ±(99.9%) 0.043 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   5.186 ms/op
                 getUser·p0.95:   5.775 ms/op
                 getUser·p0.99:   9.114 ms/op
                 getUser·p0.999:  11.796 ms/op
                 getUser·p0.9999: 11.829 ms/op
                 getUser·p1.00:   11.829 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7886
  mean =      4.062 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 217 
    [ 2.500,  3.750) = 2814 
    [ 3.750,  5.000) = 3819 
    [ 5.000,  6.250) = 741 
    [ 6.250,  7.500) = 121 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      9.114 ms/op
     p(99.9000) =     11.796 ms/op
     p(99.9900) =     11.829 ms/op
     p(99.9990) =     11.829 ms/op
     p(99.9999) =     11.829 ms/op
    p(100.0000) =     11.829 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 22.869 ±(99.9%) 0.573 ms/op
Iteration   1: 16.312 ±(99.9%) 0.206 ms/op
                 listUser·p0.00:   5.726 ms/op
                 listUser·p0.50:   16.073 ms/op
                 listUser·p0.90:   17.433 ms/op
                 listUser·p0.95:   19.939 ms/op
                 listUser·p0.99:   28.445 ms/op
                 listUser·p0.999:  36.605 ms/op
                 listUser·p0.9999: 37.945 ms/op
                 listUser·p1.00:   37.945 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1973
  mean =     16.312 ±(99.9%) 0.206 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 5 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 1479 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      5.726 ms/op
     p(50.0000) =     16.073 ms/op
     p(90.0000) =     17.433 ms/op
     p(95.0000) =     19.939 ms/op
     p(99.0000) =     28.445 ms/op
     p(99.9000) =     36.605 ms/op
     p(99.9900) =     37.945 ms/op
     p(99.9990) =     37.945 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.800          ops/ms
Client.existUser                       thrpt         6.379          ops/ms
Client.getUser                         thrpt         5.319          ops/ms
Client.listUser                        thrpt         1.481          ops/ms
Client.createUser                       avgt         6.043           ms/op
Client.existUser                        avgt         3.342           ms/op
Client.getUser                          avgt         4.345           ms/op
Client.listUser                         avgt        15.105           ms/op
Client.createUser                     sample  5860   5.471 ± 0.109   ms/op
Client.createUser:createUser·p0.00    sample         1.346           ms/op
Client.createUser:createUser·p0.50    sample         4.993           ms/op
Client.createUser:createUser·p0.90    sample         8.520           ms/op
Client.createUser:createUser·p0.95    sample        11.731           ms/op
Client.createUser:createUser·p0.99    sample        14.664           ms/op
Client.createUser:createUser·p0.999   sample        17.961           ms/op
Client.createUser:createUser·p0.9999  sample        17.990           ms/op
Client.createUser:createUser·p1.00    sample        17.990           ms/op
Client.existUser                      sample  9863   3.234 ± 0.042   ms/op
Client.existUser:existUser·p0.00      sample         0.565           ms/op
Client.existUser:existUser·p0.50      sample         3.195           ms/op
Client.existUser:existUser·p0.90      sample         3.518           ms/op
Client.existUser:existUser·p0.95      sample         3.617           ms/op
Client.existUser:existUser·p0.99      sample         6.177           ms/op
Client.existUser:existUser·p0.999     sample        20.157           ms/op
Client.existUser:existUser·p0.9999    sample        20.644           ms/op
Client.existUser:existUser·p1.00      sample        20.644           ms/op
Client.getUser                        sample  7886   4.062 ± 0.043   ms/op
Client.getUser:getUser·p0.00          sample         1.098           ms/op
Client.getUser:getUser·p0.50          sample         3.895           ms/op
Client.getUser:getUser·p0.90          sample         5.186           ms/op
Client.getUser:getUser·p0.95          sample         5.775           ms/op
Client.getUser:getUser·p0.99          sample         9.114           ms/op
Client.getUser:getUser·p0.999         sample        11.796           ms/op
Client.getUser:getUser·p0.9999        sample        11.829           ms/op
Client.getUser:getUser·p1.00          sample        11.829           ms/op
Client.listUser                       sample  1973  16.312 ± 0.206   ms/op
Client.listUser:listUser·p0.00        sample         5.726           ms/op
Client.listUser:listUser·p0.50        sample        16.073           ms/op
Client.listUser:listUser·p0.90        sample        17.433           ms/op
Client.listUser:listUser·p0.95        sample        19.939           ms/op
Client.listUser:listUser·p0.99        sample        28.445           ms/op
Client.listUser:listUser·p0.999       sample        36.605           ms/op
Client.listUser:listUser·p0.9999      sample        37.945           ms/op
Client.listUser:listUser·p1.00        sample        37.945           ms/op
