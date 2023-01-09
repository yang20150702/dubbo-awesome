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
# Warmup Iteration   1: 0.746 ops/ms
Iteration   1: 1.754 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.754 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.047 ops/ms
Iteration   1: 4.137 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.137 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.919 ops/ms
Iteration   1: 3.493 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.493 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:07
# Fork: 1 of 1
# Warmup Iteration   1: 0.720 ops/ms
Iteration   1: 1.105 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.105 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:59
# Fork: 1 of 1
# Warmup Iteration   1: 25.095 ±(99.9%) 0.338 ms/op
Iteration   1: 11.919 ±(99.9%) 0.068 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  11.919 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:52
# Fork: 1 of 1
# Warmup Iteration   1: 15.512 ±(99.9%) 0.186 ms/op
Iteration   1: 7.761 ±(99.9%) 0.143 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.761 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:44
# Fork: 1 of 1
# Warmup Iteration   1: 13.776 ±(99.9%) 0.239 ms/op
Iteration   1: 6.192 ±(99.9%) 0.047 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.192 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 38.803 ±(99.9%) 1.080 ms/op
Iteration   1: 24.186 ±(99.9%) 0.230 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  24.186 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 18.997 ±(99.9%) 1.113 ms/op
Iteration   1: 8.367 ±(99.9%) 0.263 ms/op
                 createUser·p0.00:   2.609 ms/op
                 createUser·p0.50:   7.135 ms/op
                 createUser·p0.90:   13.451 ms/op
                 createUser·p0.95:   16.545 ms/op
                 createUser·p0.99:   26.868 ms/op
                 createUser·p0.999:  44.905 ms/op
                 createUser·p0.9999: 45.482 ms/op
                 createUser·p1.00:   45.482 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 3802
  mean =      8.367 ±(99.9%) 0.263 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 756 
    [ 5.000, 10.000) = 2362 
    [10.000, 15.000) = 412 
    [15.000, 20.000) = 167 
    [20.000, 25.000) = 59 
    [25.000, 30.000) = 14 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 30 

  Percentiles, ms/op:
      p(0.0000) =      2.609 ms/op
     p(50.0000) =      7.135 ms/op
     p(90.0000) =     13.451 ms/op
     p(95.0000) =     16.545 ms/op
     p(99.0000) =     26.868 ms/op
     p(99.9000) =     44.905 ms/op
     p(99.9900) =     45.482 ms/op
     p(99.9990) =     45.482 ms/op
     p(99.9999) =     45.482 ms/op
    p(100.0000) =     45.482 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.992 ±(99.9%) 0.459 ms/op
Iteration   1: 5.174 ±(99.9%) 0.081 ms/op
                 existUser·p0.00:   1.038 ms/op
                 existUser·p0.50:   5.186 ms/op
                 existUser·p0.90:   5.812 ms/op
                 existUser·p0.95:   6.470 ms/op
                 existUser·p0.99:   14.664 ms/op
                 existUser·p0.999:  21.610 ms/op
                 existUser·p0.9999: 21.725 ms/op
                 existUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 6264
  mean =      5.174 ±(99.9%) 0.081 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 527 
    [ 2.500,  5.000) = 1740 
    [ 5.000,  7.500) = 3805 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.038 ms/op
     p(50.0000) =      5.186 ms/op
     p(90.0000) =      5.812 ms/op
     p(95.0000) =      6.470 ms/op
     p(99.0000) =     14.664 ms/op
     p(99.9000) =     21.610 ms/op
     p(99.9900) =     21.725 ms/op
     p(99.9990) =     21.725 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 13.430 ±(99.9%) 0.482 ms/op
Iteration   1: 5.640 ±(99.9%) 0.110 ms/op
                 getUser·p0.00:   1.798 ms/op
                 getUser·p0.50:   5.472 ms/op
                 getUser·p0.90:   6.423 ms/op
                 getUser·p0.95:   7.078 ms/op
                 getUser·p0.99:   18.383 ms/op
                 getUser·p0.999:  29.262 ms/op
                 getUser·p0.9999: 29.360 ms/op
                 getUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 5670
  mean =      5.640 ±(99.9%) 0.110 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 2233 
    [ 5.000,  7.500) = 3178 
    [ 7.500, 10.000) = 106 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.798 ms/op
     p(50.0000) =      5.472 ms/op
     p(90.0000) =      6.423 ms/op
     p(95.0000) =      7.078 ms/op
     p(99.0000) =     18.383 ms/op
     p(99.9000) =     29.262 ms/op
     p(99.9900) =     29.360 ms/op
     p(99.9990) =     29.360 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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
# Warmup Iteration   1: 36.136 ±(99.9%) 1.828 ms/op
Iteration   1: 27.245 ±(99.9%) 0.556 ms/op
                 listUser·p0.00:   9.339 ms/op
                 listUser·p0.50:   26.444 ms/op
                 listUser·p0.90:   33.620 ms/op
                 listUser·p0.95:   39.708 ms/op
                 listUser·p0.99:   46.556 ms/op
                 listUser·p0.999:  56.328 ms/op
                 listUser·p0.9999: 56.426 ms/op
                 listUser·p1.00:   56.426 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1186
  mean =     27.245 ±(99.9%) 0.556 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 3 
    [10.000, 15.000) = 28 
    [15.000, 20.000) = 53 
    [20.000, 25.000) = 207 
    [25.000, 30.000) = 677 
    [30.000, 35.000) = 106 
    [35.000, 40.000) = 54 
    [40.000, 45.000) = 44 
    [45.000, 50.000) = 10 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      9.339 ms/op
     p(50.0000) =     26.444 ms/op
     p(90.0000) =     33.620 ms/op
     p(95.0000) =     39.708 ms/op
     p(99.0000) =     46.556 ms/op
     p(99.9000) =     56.328 ms/op
     p(99.9900) =     56.426 ms/op
     p(99.9990) =     56.426 ms/op
     p(99.9999) =     56.426 ms/op
    p(100.0000) =     56.426 ms/op


# Run complete. Total time: 00:01:30

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.754          ops/ms
Client.existUser                       thrpt         4.137          ops/ms
Client.getUser                         thrpt         3.493          ops/ms
Client.listUser                        thrpt         1.105          ops/ms
Client.createUser                       avgt        11.919           ms/op
Client.existUser                        avgt         7.761           ms/op
Client.getUser                          avgt         6.192           ms/op
Client.listUser                         avgt        24.186           ms/op
Client.createUser                     sample  3802   8.367 ± 0.263   ms/op
Client.createUser:createUser·p0.00    sample         2.609           ms/op
Client.createUser:createUser·p0.50    sample         7.135           ms/op
Client.createUser:createUser·p0.90    sample        13.451           ms/op
Client.createUser:createUser·p0.95    sample        16.545           ms/op
Client.createUser:createUser·p0.99    sample        26.868           ms/op
Client.createUser:createUser·p0.999   sample        44.905           ms/op
Client.createUser:createUser·p0.9999  sample        45.482           ms/op
Client.createUser:createUser·p1.00    sample        45.482           ms/op
Client.existUser                      sample  6264   5.174 ± 0.081   ms/op
Client.existUser:existUser·p0.00      sample         1.038           ms/op
Client.existUser:existUser·p0.50      sample         5.186           ms/op
Client.existUser:existUser·p0.90      sample         5.812           ms/op
Client.existUser:existUser·p0.95      sample         6.470           ms/op
Client.existUser:existUser·p0.99      sample        14.664           ms/op
Client.existUser:existUser·p0.999     sample        21.610           ms/op
Client.existUser:existUser·p0.9999    sample        21.725           ms/op
Client.existUser:existUser·p1.00      sample        21.725           ms/op
Client.getUser                        sample  5670   5.640 ± 0.110   ms/op
Client.getUser:getUser·p0.00          sample         1.798           ms/op
Client.getUser:getUser·p0.50          sample         5.472           ms/op
Client.getUser:getUser·p0.90          sample         6.423           ms/op
Client.getUser:getUser·p0.95          sample         7.078           ms/op
Client.getUser:getUser·p0.99          sample        18.383           ms/op
Client.getUser:getUser·p0.999         sample        29.262           ms/op
Client.getUser:getUser·p0.9999        sample        29.360           ms/op
Client.getUser:getUser·p1.00          sample        29.360           ms/op
Client.listUser                       sample  1186  27.245 ± 0.556   ms/op
Client.listUser:listUser·p0.00        sample         9.339           ms/op
Client.listUser:listUser·p0.50        sample        26.444           ms/op
Client.listUser:listUser·p0.90        sample        33.620           ms/op
Client.listUser:listUser·p0.95        sample        39.708           ms/op
Client.listUser:listUser·p0.99        sample        46.556           ms/op
Client.listUser:listUser·p0.999       sample        56.328           ms/op
Client.listUser:listUser·p0.9999      sample        56.426           ms/op
Client.listUser:listUser·p1.00        sample        56.426           ms/op
