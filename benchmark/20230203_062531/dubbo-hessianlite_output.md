# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.110 ops/ms
Iteration   1: 2.398 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.398 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 2.722 ops/ms
Iteration   1: 6.596 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.596 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.107 ops/ms
Iteration   1: 4.985 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.985 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 0.909 ops/ms
Iteration   1: 1.152 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.152 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 15.212 ±(99.9%) 0.279 ms/op
Iteration   1: 8.092 ±(99.9%) 0.058 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  8.092 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.660 ±(99.9%) 0.084 ms/op
Iteration   1: 4.381 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.381 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.978 ±(99.9%) 0.159 ms/op
Iteration   1: 5.512 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.512 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 31.896 ±(99.9%) 1.097 ms/op
Iteration   1: 20.050 ±(99.9%) 0.039 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  20.050 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 13.622 ±(99.9%) 0.493 ms/op
Iteration   1: 6.332 ±(99.9%) 0.157 ms/op
                 createUser·p0.00:   1.589 ms/op
                 createUser·p0.50:   5.947 ms/op
                 createUser·p0.90:   8.762 ms/op
                 createUser·p0.95:   14.696 ms/op
                 createUser·p0.99:   19.661 ms/op
                 createUser·p0.999:  29.032 ms/op
                 createUser·p0.9999: 29.065 ms/op
                 createUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5057
  mean =      6.332 ±(99.9%) 0.157 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 1460 
    [ 5.000,  7.500) = 2904 
    [ 7.500, 10.000) = 247 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.589 ms/op
     p(50.0000) =      5.947 ms/op
     p(90.0000) =      8.762 ms/op
     p(95.0000) =     14.696 ms/op
     p(99.0000) =     19.661 ms/op
     p(99.9000) =     29.032 ms/op
     p(99.9900) =     29.065 ms/op
     p(99.9990) =     29.065 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.623 ±(99.9%) 0.203 ms/op
Iteration   1: 3.972 ±(99.9%) 0.064 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   3.867 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   6.002 ms/op
                 existUser·p0.99:   13.189 ms/op
                 existUser·p0.999:  14.303 ms/op
                 existUser·p0.9999: 30.409 ms/op
                 existUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8105
  mean =      3.972 ±(99.9%) 0.064 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 927 
    [ 2.500,  5.000) = 6692 
    [ 5.000,  7.500) = 215 
    [ 7.500, 10.000) = 105 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      6.002 ms/op
     p(99.0000) =     13.189 ms/op
     p(99.9000) =     14.303 ms/op
     p(99.9900) =     30.409 ms/op
     p(99.9990) =     30.409 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 10.378 ±(99.9%) 0.348 ms/op
Iteration   1: 5.048 ±(99.9%) 0.082 ms/op
                 getUser·p0.00:   1.755 ms/op
                 getUser·p0.50:   4.784 ms/op
                 getUser·p0.90:   5.751 ms/op
                 getUser·p0.95:   6.797 ms/op
                 getUser·p0.99:   13.241 ms/op
                 getUser·p0.999:  28.497 ms/op
                 getUser·p0.9999: 29.295 ms/op
                 getUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6345
  mean =      5.048 ±(99.9%) 0.082 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 3967 
    [ 5.000,  7.500) = 2146 
    [ 7.500, 10.000) = 121 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.755 ms/op
     p(50.0000) =      4.784 ms/op
     p(90.0000) =      5.751 ms/op
     p(95.0000) =      6.797 ms/op
     p(99.0000) =     13.241 ms/op
     p(99.9000) =     28.497 ms/op
     p(99.9900) =     29.295 ms/op
     p(99.9990) =     29.295 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 26.766 ±(99.9%) 0.843 ms/op
Iteration   1: 19.220 ±(99.9%) 0.254 ms/op
                 listUser·p0.00:   8.454 ms/op
                 listUser·p0.50:   18.776 ms/op
                 listUser·p0.90:   22.512 ms/op
                 listUser·p0.95:   24.084 ms/op
                 listUser·p0.99:   30.282 ms/op
                 listUser·p0.999:  35.619 ms/op
                 listUser·p0.9999: 35.979 ms/op
                 listUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1687
  mean =     19.220 ±(99.9%) 0.254 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 847 
    [20.000, 22.500) = 354 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      8.454 ms/op
     p(50.0000) =     18.776 ms/op
     p(90.0000) =     22.512 ms/op
     p(95.0000) =     24.084 ms/op
     p(99.0000) =     30.282 ms/op
     p(99.9000) =     35.619 ms/op
     p(99.9900) =     35.979 ms/op
     p(99.9990) =     35.979 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.398          ops/ms
Client.existUser                       thrpt         6.596          ops/ms
Client.getUser                         thrpt         4.985          ops/ms
Client.listUser                        thrpt         1.152          ops/ms
Client.createUser                       avgt         8.092           ms/op
Client.existUser                        avgt         4.381           ms/op
Client.getUser                          avgt         5.512           ms/op
Client.listUser                         avgt        20.050           ms/op
Client.createUser                     sample  5057   6.332 ± 0.157   ms/op
Client.createUser:createUser·p0.00    sample         1.589           ms/op
Client.createUser:createUser·p0.50    sample         5.947           ms/op
Client.createUser:createUser·p0.90    sample         8.762           ms/op
Client.createUser:createUser·p0.95    sample        14.696           ms/op
Client.createUser:createUser·p0.99    sample        19.661           ms/op
Client.createUser:createUser·p0.999   sample        29.032           ms/op
Client.createUser:createUser·p0.9999  sample        29.065           ms/op
Client.createUser:createUser·p1.00    sample        29.065           ms/op
Client.existUser                      sample  8105   3.972 ± 0.064   ms/op
Client.existUser:existUser·p0.00      sample         1.085           ms/op
Client.existUser:existUser·p0.50      sample         3.867           ms/op
Client.existUser:existUser·p0.90      sample         4.399           ms/op
Client.existUser:existUser·p0.95      sample         6.002           ms/op
Client.existUser:existUser·p0.99      sample        13.189           ms/op
Client.existUser:existUser·p0.999     sample        14.303           ms/op
Client.existUser:existUser·p0.9999    sample        30.409           ms/op
Client.existUser:existUser·p1.00      sample        30.409           ms/op
Client.getUser                        sample  6345   5.048 ± 0.082   ms/op
Client.getUser:getUser·p0.00          sample         1.755           ms/op
Client.getUser:getUser·p0.50          sample         4.784           ms/op
Client.getUser:getUser·p0.90          sample         5.751           ms/op
Client.getUser:getUser·p0.95          sample         6.797           ms/op
Client.getUser:getUser·p0.99          sample        13.241           ms/op
Client.getUser:getUser·p0.999         sample        28.497           ms/op
Client.getUser:getUser·p0.9999        sample        29.295           ms/op
Client.getUser:getUser·p1.00          sample        29.295           ms/op
Client.listUser                       sample  1687  19.220 ± 0.254   ms/op
Client.listUser:listUser·p0.00        sample         8.454           ms/op
Client.listUser:listUser·p0.50        sample        18.776           ms/op
Client.listUser:listUser·p0.90        sample        22.512           ms/op
Client.listUser:listUser·p0.95        sample        24.084           ms/op
Client.listUser:listUser·p0.99        sample        30.282           ms/op
Client.listUser:listUser·p0.999       sample        35.619           ms/op
Client.listUser:listUser·p0.9999      sample        35.979           ms/op
Client.listUser:listUser·p1.00        sample        35.979           ms/op
