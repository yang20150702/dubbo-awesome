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
# Warmup Iteration   1: 1.232 ops/ms
Iteration   1: 2.939 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.939 ops/ms


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
# Warmup Iteration   1: 3.398 ops/ms
Iteration   1: 7.057 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.057 ops/ms


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
# Warmup Iteration   1: 2.624 ops/ms
Iteration   1: 4.287 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.287 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.897 ops/ms
Iteration   1: 1.558 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.558 ops/ms


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
# Warmup Iteration   1: 14.812 ±(99.9%) 0.165 ms/op
Iteration   1: 7.204 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.204 ms/op


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
# Warmup Iteration   1: 7.852 ±(99.9%) 0.091 ms/op
Iteration   1: 3.535 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.535 ms/op


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
# Warmup Iteration   1: 9.415 ±(99.9%) 0.118 ms/op
Iteration   1: 4.428 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.428 ms/op


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
# Warmup Iteration   1: 23.372 ±(99.9%) 0.366 ms/op
Iteration   1: 15.591 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.591 ms/op


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
# Warmup Iteration   1: 13.701 ±(99.9%) 0.485 ms/op
Iteration   1: 6.455 ±(99.9%) 0.170 ms/op
                 createUser·p0.00:   2.544 ms/op
                 createUser·p0.50:   5.480 ms/op
                 createUser·p0.90:   8.962 ms/op
                 createUser·p0.95:   14.669 ms/op
                 createUser·p0.99:   25.305 ms/op
                 createUser·p0.999:  27.761 ms/op
                 createUser·p0.9999: 31.425 ms/op
                 createUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4973
  mean =      6.455 ±(99.9%) 0.170 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 842 
    [ 5.000,  7.500) = 3523 
    [ 7.500, 10.000) = 174 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.544 ms/op
     p(50.0000) =      5.480 ms/op
     p(90.0000) =      8.962 ms/op
     p(95.0000) =     14.669 ms/op
     p(99.0000) =     25.305 ms/op
     p(99.9000) =     27.761 ms/op
     p(99.9900) =     31.425 ms/op
     p(99.9990) =     31.425 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


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
# Warmup Iteration   1: 6.521 ±(99.9%) 0.192 ms/op
Iteration   1: 3.748 ±(99.9%) 0.067 ms/op
                 existUser·p0.00:   1.042 ms/op
                 existUser·p0.50:   3.596 ms/op
                 existUser·p0.90:   4.055 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   11.308 ms/op
                 existUser·p0.999:  26.983 ms/op
                 existUser·p0.9999: 27.296 ms/op
                 existUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8541
  mean =      3.748 ±(99.9%) 0.067 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 945 
    [ 2.500,  5.000) = 7220 
    [ 5.000,  7.500) = 166 
    [ 7.500, 10.000) = 80 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.042 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =     11.308 ms/op
     p(99.9000) =     26.983 ms/op
     p(99.9900) =     27.296 ms/op
     p(99.9990) =     27.296 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 8.986 ±(99.9%) 0.374 ms/op
Iteration   1: 4.152 ±(99.9%) 0.043 ms/op
                 getUser·p0.00:   1.034 ms/op
                 getUser·p0.50:   3.940 ms/op
                 getUser·p0.90:   4.899 ms/op
                 getUser·p0.95:   5.407 ms/op
                 getUser·p0.99:   10.406 ms/op
                 getUser·p0.999:  16.434 ms/op
                 getUser·p0.9999: 18.547 ms/op
                 getUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7841
  mean =      4.152 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 34 
    [ 2.500,  3.750) = 2546 
    [ 3.750,  5.000) = 4571 
    [ 5.000,  6.250) = 510 
    [ 6.250,  7.500) = 81 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.034 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =     10.406 ms/op
     p(99.9000) =     16.434 ms/op
     p(99.9900) =     18.547 ms/op
     p(99.9990) =     18.547 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 27.162 ±(99.9%) 0.891 ms/op
Iteration   1: 14.069 ±(99.9%) 0.167 ms/op
                 listUser·p0.00:   4.473 ms/op
                 listUser·p0.50:   13.271 ms/op
                 listUser·p0.90:   16.132 ms/op
                 listUser·p0.95:   19.199 ms/op
                 listUser·p0.99:   24.117 ms/op
                 listUser·p0.999:  29.163 ms/op
                 listUser·p0.9999: 29.884 ms/op
                 listUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2281
  mean =     14.069 ±(99.9%) 0.167 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 2 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 23 
    [10.000, 12.500) = 345 
    [12.500, 15.000) = 1316 
    [15.000, 17.500) = 399 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      4.473 ms/op
     p(50.0000) =     13.271 ms/op
     p(90.0000) =     16.132 ms/op
     p(95.0000) =     19.199 ms/op
     p(99.0000) =     24.117 ms/op
     p(99.9000) =     29.163 ms/op
     p(99.9900) =     29.884 ms/op
     p(99.9990) =     29.884 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.939          ops/ms
Client.existUser                       thrpt         7.057          ops/ms
Client.getUser                         thrpt         4.287          ops/ms
Client.listUser                        thrpt         1.558          ops/ms
Client.createUser                       avgt         7.204           ms/op
Client.existUser                        avgt         3.535           ms/op
Client.getUser                          avgt         4.428           ms/op
Client.listUser                         avgt        15.591           ms/op
Client.createUser                     sample  4973   6.455 ± 0.170   ms/op
Client.createUser:createUser·p0.00    sample         2.544           ms/op
Client.createUser:createUser·p0.50    sample         5.480           ms/op
Client.createUser:createUser·p0.90    sample         8.962           ms/op
Client.createUser:createUser·p0.95    sample        14.669           ms/op
Client.createUser:createUser·p0.99    sample        25.305           ms/op
Client.createUser:createUser·p0.999   sample        27.761           ms/op
Client.createUser:createUser·p0.9999  sample        31.425           ms/op
Client.createUser:createUser·p1.00    sample        31.425           ms/op
Client.existUser                      sample  8541   3.748 ± 0.067   ms/op
Client.existUser:existUser·p0.00      sample         1.042           ms/op
Client.existUser:existUser·p0.50      sample         3.596           ms/op
Client.existUser:existUser·p0.90      sample         4.055           ms/op
Client.existUser:existUser·p0.95      sample         4.506           ms/op
Client.existUser:existUser·p0.99      sample        11.308           ms/op
Client.existUser:existUser·p0.999     sample        26.983           ms/op
Client.existUser:existUser·p0.9999    sample        27.296           ms/op
Client.existUser:existUser·p1.00      sample        27.296           ms/op
Client.getUser                        sample  7841   4.152 ± 0.043   ms/op
Client.getUser:getUser·p0.00          sample         1.034           ms/op
Client.getUser:getUser·p0.50          sample         3.940           ms/op
Client.getUser:getUser·p0.90          sample         4.899           ms/op
Client.getUser:getUser·p0.95          sample         5.407           ms/op
Client.getUser:getUser·p0.99          sample        10.406           ms/op
Client.getUser:getUser·p0.999         sample        16.434           ms/op
Client.getUser:getUser·p0.9999        sample        18.547           ms/op
Client.getUser:getUser·p1.00          sample        18.547           ms/op
Client.listUser                       sample  2281  14.069 ± 0.167   ms/op
Client.listUser:listUser·p0.00        sample         4.473           ms/op
Client.listUser:listUser·p0.50        sample        13.271           ms/op
Client.listUser:listUser·p0.90        sample        16.132           ms/op
Client.listUser:listUser·p0.95        sample        19.199           ms/op
Client.listUser:listUser·p0.99        sample        24.117           ms/op
Client.listUser:listUser·p0.999       sample        29.163           ms/op
Client.listUser:listUser·p0.9999      sample        29.884           ms/op
Client.listUser:listUser·p1.00        sample        29.884           ms/op
