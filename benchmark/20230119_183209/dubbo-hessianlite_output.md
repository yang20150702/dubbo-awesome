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
# Warmup Iteration   1: 1.021 ops/ms
Iteration   1: 2.659 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.659 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.103 ops/ms
Iteration   1: 7.837 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.837 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.592 ops/ms
Iteration   1: 5.284 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.284 ops/ms


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
# Warmup Iteration   1: 0.946 ops/ms
Iteration   1: 1.514 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.514 ops/ms


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
# Warmup Iteration   1: 16.891 ±(99.9%) 0.238 ms/op
Iteration   1: 6.214 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.214 ms/op


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
# Warmup Iteration   1: 6.213 ±(99.9%) 0.079 ms/op
Iteration   1: 4.053 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.053 ms/op


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
# Warmup Iteration   1: 10.044 ±(99.9%) 0.163 ms/op
Iteration   1: 4.786 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.786 ms/op


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
# Warmup Iteration   1: 27.545 ±(99.9%) 0.404 ms/op
Iteration   1: 15.972 ±(99.9%) 0.130 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.972 ms/op


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
# Warmup Iteration   1: 12.606 ±(99.9%) 0.475 ms/op
Iteration   1: 6.606 ±(99.9%) 0.121 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   6.513 ms/op
                 createUser·p0.90:   7.250 ms/op
                 createUser·p0.95:   8.798 ms/op
                 createUser·p0.99:   21.004 ms/op
                 createUser·p0.999:  24.930 ms/op
                 createUser·p0.9999: 28.803 ms/op
                 createUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4835
  mean =      6.606 ±(99.9%) 0.121 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 213 
    [ 2.500,  5.000) = 169 
    [ 5.000,  7.500) = 4091 
    [ 7.500, 10.000) = 191 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      6.513 ms/op
     p(90.0000) =      7.250 ms/op
     p(95.0000) =      8.798 ms/op
     p(99.0000) =     21.004 ms/op
     p(99.9000) =     24.930 ms/op
     p(99.9900) =     28.803 ms/op
     p(99.9990) =     28.803 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


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
# Warmup Iteration   1: 6.920 ±(99.9%) 0.230 ms/op
Iteration   1: 3.447 ±(99.9%) 0.054 ms/op
                 existUser·p0.00:   0.418 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   12.927 ms/op
                 existUser·p0.999:  19.857 ms/op
                 existUser·p0.9999: 19.857 ms/op
                 existUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9289
  mean =      3.447 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 846 
    [ 2.500,  3.750) = 7515 
    [ 3.750,  5.000) = 544 
    [ 5.000,  6.250) = 91 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.418 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =     12.927 ms/op
     p(99.9000) =     19.857 ms/op
     p(99.9900) =     19.857 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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
# Warmup Iteration   1: 9.242 ±(99.9%) 0.404 ms/op
Iteration   1: 4.295 ±(99.9%) 0.083 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   3.949 ms/op
                 getUser·p0.90:   5.329 ms/op
                 getUser·p0.95:   7.320 ms/op
                 getUser·p0.99:   12.965 ms/op
                 getUser·p0.999:  24.546 ms/op
                 getUser·p0.9999: 29.753 ms/op
                 getUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7454
  mean =      4.295 ±(99.9%) 0.083 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 439 
    [ 2.500,  5.000) = 6070 
    [ 5.000,  7.500) = 598 
    [ 7.500, 10.000) = 155 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      5.329 ms/op
     p(95.0000) =      7.320 ms/op
     p(99.0000) =     12.965 ms/op
     p(99.9000) =     24.546 ms/op
     p(99.9900) =     29.753 ms/op
     p(99.9990) =     29.753 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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
# Warmup Iteration   1: 25.596 ±(99.9%) 0.967 ms/op
Iteration   1: 15.419 ±(99.9%) 0.254 ms/op
                 listUser·p0.00:   6.988 ms/op
                 listUser·p0.50:   15.516 ms/op
                 listUser·p0.90:   17.334 ms/op
                 listUser·p0.95:   22.921 ms/op
                 listUser·p0.99:   28.443 ms/op
                 listUser·p0.999:  34.134 ms/op
                 listUser·p0.9999: 34.210 ms/op
                 listUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2077
  mean =     15.419 ±(99.9%) 0.254 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 59 
    [10.000, 12.500) = 199 
    [12.500, 15.000) = 383 
    [15.000, 17.500) = 1225 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      6.988 ms/op
     p(50.0000) =     15.516 ms/op
     p(90.0000) =     17.334 ms/op
     p(95.0000) =     22.921 ms/op
     p(99.0000) =     28.443 ms/op
     p(99.9000) =     34.134 ms/op
     p(99.9900) =     34.210 ms/op
     p(99.9990) =     34.210 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.659          ops/ms
Client.existUser                       thrpt         7.837          ops/ms
Client.getUser                         thrpt         5.284          ops/ms
Client.listUser                        thrpt         1.514          ops/ms
Client.createUser                       avgt         6.214           ms/op
Client.existUser                        avgt         4.053           ms/op
Client.getUser                          avgt         4.786           ms/op
Client.listUser                         avgt        15.972           ms/op
Client.createUser                     sample  4835   6.606 ± 0.121   ms/op
Client.createUser:createUser·p0.00    sample         1.141           ms/op
Client.createUser:createUser·p0.50    sample         6.513           ms/op
Client.createUser:createUser·p0.90    sample         7.250           ms/op
Client.createUser:createUser·p0.95    sample         8.798           ms/op
Client.createUser:createUser·p0.99    sample        21.004           ms/op
Client.createUser:createUser·p0.999   sample        24.930           ms/op
Client.createUser:createUser·p0.9999  sample        28.803           ms/op
Client.createUser:createUser·p1.00    sample        28.803           ms/op
Client.existUser                      sample  9289   3.447 ± 0.054   ms/op
Client.existUser:existUser·p0.00      sample         0.418           ms/op
Client.existUser:existUser·p0.50      sample         3.305           ms/op
Client.existUser:existUser·p0.90      sample         3.731           ms/op
Client.existUser:existUser·p0.95      sample         4.157           ms/op
Client.existUser:existUser·p0.99      sample        12.927           ms/op
Client.existUser:existUser·p0.999     sample        19.857           ms/op
Client.existUser:existUser·p0.9999    sample        19.857           ms/op
Client.existUser:existUser·p1.00      sample        19.857           ms/op
Client.getUser                        sample  7454   4.295 ± 0.083   ms/op
Client.getUser:getUser·p0.00          sample         1.317           ms/op
Client.getUser:getUser·p0.50          sample         3.949           ms/op
Client.getUser:getUser·p0.90          sample         5.329           ms/op
Client.getUser:getUser·p0.95          sample         7.320           ms/op
Client.getUser:getUser·p0.99          sample        12.965           ms/op
Client.getUser:getUser·p0.999         sample        24.546           ms/op
Client.getUser:getUser·p0.9999        sample        29.753           ms/op
Client.getUser:getUser·p1.00          sample        29.753           ms/op
Client.listUser                       sample  2077  15.419 ± 0.254   ms/op
Client.listUser:listUser·p0.00        sample         6.988           ms/op
Client.listUser:listUser·p0.50        sample        15.516           ms/op
Client.listUser:listUser·p0.90        sample        17.334           ms/op
Client.listUser:listUser·p0.95        sample        22.921           ms/op
Client.listUser:listUser·p0.99        sample        28.443           ms/op
Client.listUser:listUser·p0.999       sample        34.134           ms/op
Client.listUser:listUser·p0.9999      sample        34.210           ms/op
Client.listUser:listUser·p1.00        sample        34.210           ms/op
