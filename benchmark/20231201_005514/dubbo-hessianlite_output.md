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
# Warmup Iteration   1: 2.428 ops/ms
Iteration   1: 6.038 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.038 ops/ms


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
# Warmup Iteration   1: 5.995 ops/ms
Iteration   1: 12.243 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.243 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.113 ops/ms
Iteration   1: 9.680 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.680 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.374 ops/ms
Iteration   1: 3.321 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.321 ops/ms


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
# Warmup Iteration   1: 5.260 ±(99.9%) 0.078 ms/op
Iteration   1: 3.057 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.057 ms/op


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
# Warmup Iteration   1: 2.930 ±(99.9%) 0.034 ms/op
Iteration   1: 1.763 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.763 ms/op


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
# Warmup Iteration   1: 4.472 ±(99.9%) 0.048 ms/op
Iteration   1: 2.850 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.850 ms/op


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
# Warmup Iteration   1: 13.483 ±(99.9%) 0.242 ms/op
Iteration   1: 8.040 ±(99.9%) 0.115 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.040 ms/op


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
# Warmup Iteration   1: 4.938 ±(99.9%) 0.113 ms/op
Iteration   1: 2.771 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   5.624 ms/op
                 createUser·p0.999:  26.575 ms/op
                 createUser·p0.9999: 27.074 ms/op
                 createUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11547
  mean =      2.771 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4719 
    [ 2.500,  5.000) = 6666 
    [ 5.000,  7.500) = 120 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.972 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      5.624 ms/op
     p(99.9000) =     26.575 ms/op
     p(99.9900) =     27.074 ms/op
     p(99.9990) =     27.099 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


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
# Warmup Iteration   1: 3.151 ±(99.9%) 0.090 ms/op
Iteration   1: 1.889 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.308 ms/op
                 existUser·p0.50:   1.839 ms/op
                 existUser·p0.90:   2.466 ms/op
                 existUser·p0.95:   2.745 ms/op
                 existUser·p0.99:   3.465 ms/op
                 existUser·p0.999:  6.350 ms/op
                 existUser·p0.9999: 7.376 ms/op
                 existUser·p1.00:   8.339 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16916
  mean =      1.889 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 5 
    [0.500, 1.000) = 111 
    [1.000, 1.500) = 3704 
    [1.500, 2.000) = 7267 
    [2.000, 2.500) = 4274 
    [2.500, 3.000) = 1044 
    [3.000, 3.500) = 353 
    [3.500, 4.000) = 77 
    [4.000, 4.500) = 40 
    [4.500, 5.000) = 1 
    [5.000, 5.500) = 8 
    [5.500, 6.000) = 7 
    [6.000, 6.500) = 13 
    [6.500, 7.000) = 11 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.308 ms/op
     p(50.0000) =      1.839 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.745 ms/op
     p(99.0000) =      3.465 ms/op
     p(99.9000) =      6.350 ms/op
     p(99.9900) =      7.376 ms/op
     p(99.9990) =      8.339 ms/op
     p(99.9999) =      8.339 ms/op
    p(100.0000) =      8.339 ms/op


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
# Warmup Iteration   1: 4.257 ±(99.9%) 0.109 ms/op
Iteration   1: 3.207 ±(99.9%) 0.053 ms/op
                 getUser·p0.00:   0.646 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   4.059 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   8.563 ms/op
                 getUser·p0.999:  22.970 ms/op
                 getUser·p0.9999: 23.331 ms/op
                 getUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10138
  mean =      3.207 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2687 
    [ 2.500,  5.000) = 6955 
    [ 5.000,  7.500) = 376 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      8.563 ms/op
     p(99.9000) =     22.970 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     23.331 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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
# Warmup Iteration   1: 11.786 ±(99.9%) 0.418 ms/op
Iteration   1: 7.663 ±(99.9%) 0.123 ms/op
                 listUser·p0.00:   1.905 ms/op
                 listUser·p0.50:   7.225 ms/op
                 listUser·p0.90:   10.289 ms/op
                 listUser·p0.95:   11.928 ms/op
                 listUser·p0.99:   18.186 ms/op
                 listUser·p0.999:  21.004 ms/op
                 listUser·p0.9999: 22.020 ms/op
                 listUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4168
  mean =      7.663 ±(99.9%) 0.123 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 277 
    [ 5.000,  7.500) = 2050 
    [ 7.500, 10.000) = 1359 
    [10.000, 12.500) = 308 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.905 ms/op
     p(50.0000) =      7.225 ms/op
     p(90.0000) =     10.289 ms/op
     p(95.0000) =     11.928 ms/op
     p(99.0000) =     18.186 ms/op
     p(99.9000) =     21.004 ms/op
     p(99.9900) =     22.020 ms/op
     p(99.9990) =     22.020 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.038          ops/ms
Client.existUser                       thrpt         12.243          ops/ms
Client.getUser                         thrpt          9.680          ops/ms
Client.listUser                        thrpt          3.321          ops/ms
Client.createUser                       avgt          3.057           ms/op
Client.existUser                        avgt          1.763           ms/op
Client.getUser                          avgt          2.850           ms/op
Client.listUser                         avgt          8.040           ms/op
Client.createUser                     sample  11547   2.771 ± 0.043   ms/op
Client.createUser:createUser·p0.00    sample          0.972           ms/op
Client.createUser:createUser·p0.50    sample          2.572           ms/op
Client.createUser:createUser·p0.90    sample          3.441           ms/op
Client.createUser:createUser·p0.95    sample          3.953           ms/op
Client.createUser:createUser·p0.99    sample          5.624           ms/op
Client.createUser:createUser·p0.999   sample         26.575           ms/op
Client.createUser:createUser·p0.9999  sample         27.074           ms/op
Client.createUser:createUser·p1.00    sample         27.099           ms/op
Client.existUser                      sample  16916   1.889 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.308           ms/op
Client.existUser:existUser·p0.50      sample          1.839           ms/op
Client.existUser:existUser·p0.90      sample          2.466           ms/op
Client.existUser:existUser·p0.95      sample          2.745           ms/op
Client.existUser:existUser·p0.99      sample          3.465           ms/op
Client.existUser:existUser·p0.999     sample          6.350           ms/op
Client.existUser:existUser·p0.9999    sample          7.376           ms/op
Client.existUser:existUser·p1.00      sample          8.339           ms/op
Client.getUser                        sample  10138   3.207 ± 0.053   ms/op
Client.getUser:getUser·p0.00          sample          0.646           ms/op
Client.getUser:getUser·p0.50          sample          3.015           ms/op
Client.getUser:getUser·p0.90          sample          4.059           ms/op
Client.getUser:getUser·p0.95          sample          4.956           ms/op
Client.getUser:getUser·p0.99          sample          8.563           ms/op
Client.getUser:getUser·p0.999         sample         22.970           ms/op
Client.getUser:getUser·p0.9999        sample         23.331           ms/op
Client.getUser:getUser·p1.00          sample         23.331           ms/op
Client.listUser                       sample   4168   7.663 ± 0.123   ms/op
Client.listUser:listUser·p0.00        sample          1.905           ms/op
Client.listUser:listUser·p0.50        sample          7.225           ms/op
Client.listUser:listUser·p0.90        sample         10.289           ms/op
Client.listUser:listUser·p0.95        sample         11.928           ms/op
Client.listUser:listUser·p0.99        sample         18.186           ms/op
Client.listUser:listUser·p0.999       sample         21.004           ms/op
Client.listUser:listUser·p0.9999      sample         22.020           ms/op
Client.listUser:listUser·p1.00        sample         22.020           ms/op
