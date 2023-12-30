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
# Warmup Iteration   1: 2.639 ops/ms
Iteration   1: 6.260 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.260 ops/ms


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
# Warmup Iteration   1: 5.514 ops/ms
Iteration   1: 12.960 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.960 ops/ms


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
# Warmup Iteration   1: 4.322 ops/ms
Iteration   1: 8.947 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.947 ops/ms


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
# Warmup Iteration   1: 2.187 ops/ms
Iteration   1: 3.598 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.598 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.403 ±(99.9%) 0.093 ms/op
Iteration   1: 3.284 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.284 ms/op


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
# Warmup Iteration   1: 3.299 ±(99.9%) 0.034 ms/op
Iteration   1: 1.762 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.762 ms/op


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
# Warmup Iteration   1: 5.010 ±(99.9%) 0.103 ms/op
Iteration   1: 3.296 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.296 ms/op


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
# Warmup Iteration   1: 12.337 ±(99.9%) 0.221 ms/op
Iteration   1: 8.460 ±(99.9%) 0.095 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.460 ms/op


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
# Warmup Iteration   1: 5.229 ±(99.9%) 0.109 ms/op
Iteration   1: 3.214 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   1.253 ms/op
                 createUser·p0.50:   2.781 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   5.471 ms/op
                 createUser·p0.99:   10.827 ms/op
                 createUser·p0.999:  13.828 ms/op
                 createUser·p0.9999: 15.906 ms/op
                 createUser·p1.00:   15.909 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10116
  mean =      3.214 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2911 
    [ 2.500,  3.750) = 5809 
    [ 3.750,  5.000) = 808 
    [ 5.000,  6.250) = 162 
    [ 6.250,  7.500) = 103 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      2.781 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      5.471 ms/op
     p(99.0000) =     10.827 ms/op
     p(99.9000) =     13.828 ms/op
     p(99.9900) =     15.906 ms/op
     p(99.9990) =     15.909 ms/op
     p(99.9999) =     15.909 ms/op
    p(100.0000) =     15.909 ms/op


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
# Warmup Iteration   1: 3.177 ±(99.9%) 0.066 ms/op
Iteration   1: 1.724 ±(99.9%) 0.037 ms/op
                 existUser·p0.00:   0.313 ms/op
                 existUser·p0.50:   1.597 ms/op
                 existUser·p0.90:   2.175 ms/op
                 existUser·p0.95:   2.327 ms/op
                 existUser·p0.99:   2.716 ms/op
                 existUser·p0.999:  36.796 ms/op
                 existUser·p0.9999: 39.482 ms/op
                 existUser·p1.00:   39.649 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18531
  mean =      1.724 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18123 
    [ 2.500,  5.000) = 344 
    [ 5.000,  7.500) = 32 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.313 ms/op
     p(50.0000) =      1.597 ms/op
     p(90.0000) =      2.175 ms/op
     p(95.0000) =      2.327 ms/op
     p(99.0000) =      2.716 ms/op
     p(99.9000) =     36.796 ms/op
     p(99.9900) =     39.482 ms/op
     p(99.9990) =     39.649 ms/op
     p(99.9999) =     39.649 ms/op
    p(100.0000) =     39.649 ms/op


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
# Warmup Iteration   1: 4.600 ±(99.9%) 0.121 ms/op
Iteration   1: 3.169 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.454 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.288 ms/op
                 getUser·p0.999:  7.922 ms/op
                 getUser·p0.9999: 8.028 ms/op
                 getUser·p1.00:   8.028 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10078
  mean =      3.169 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 1 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 57 
    [1.500, 2.000) = 388 
    [2.000, 2.500) = 946 
    [2.500, 3.000) = 2207 
    [3.000, 3.500) = 3948 
    [3.500, 4.000) = 1761 
    [4.000, 4.500) = 529 
    [4.500, 5.000) = 116 
    [5.000, 5.500) = 27 
    [5.500, 6.000) = 55 
    [6.000, 6.500) = 5 
    [6.500, 7.000) = 4 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 29 
    [8.000, 8.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.454 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.288 ms/op
     p(99.9000) =      7.922 ms/op
     p(99.9900) =      8.028 ms/op
     p(99.9990) =      8.028 ms/op
     p(99.9999) =      8.028 ms/op
    p(100.0000) =      8.028 ms/op


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
# Warmup Iteration   1: 12.562 ±(99.9%) 0.430 ms/op
Iteration   1: 8.027 ±(99.9%) 0.116 ms/op
                 listUser·p0.00:   2.449 ms/op
                 listUser·p0.50:   7.766 ms/op
                 listUser·p0.90:   10.581 ms/op
                 listUser·p0.95:   11.813 ms/op
                 listUser·p0.99:   15.925 ms/op
                 listUser·p0.999:  23.635 ms/op
                 listUser·p0.9999: 24.412 ms/op
                 listUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3981
  mean =      8.027 ±(99.9%) 0.116 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 182 
    [ 5.000,  7.500) = 1579 
    [ 7.500, 10.000) = 1636 
    [10.000, 12.500) = 442 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.449 ms/op
     p(50.0000) =      7.766 ms/op
     p(90.0000) =     10.581 ms/op
     p(95.0000) =     11.813 ms/op
     p(99.0000) =     15.925 ms/op
     p(99.9000) =     23.635 ms/op
     p(99.9900) =     24.412 ms/op
     p(99.9990) =     24.412 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.260          ops/ms
Client.existUser                       thrpt         12.960          ops/ms
Client.getUser                         thrpt          8.947          ops/ms
Client.listUser                        thrpt          3.598          ops/ms
Client.createUser                       avgt          3.284           ms/op
Client.existUser                        avgt          1.762           ms/op
Client.getUser                          avgt          3.296           ms/op
Client.listUser                         avgt          8.460           ms/op
Client.createUser                     sample  10116   3.214 ± 0.052   ms/op
Client.createUser:createUser·p0.00    sample          1.253           ms/op
Client.createUser:createUser·p0.50    sample          2.781           ms/op
Client.createUser:createUser·p0.90    sample          3.928           ms/op
Client.createUser:createUser·p0.95    sample          5.471           ms/op
Client.createUser:createUser·p0.99    sample         10.827           ms/op
Client.createUser:createUser·p0.999   sample         13.828           ms/op
Client.createUser:createUser·p0.9999  sample         15.906           ms/op
Client.createUser:createUser·p1.00    sample         15.909           ms/op
Client.existUser                      sample  18531   1.724 ± 0.037   ms/op
Client.existUser:existUser·p0.00      sample          0.313           ms/op
Client.existUser:existUser·p0.50      sample          1.597           ms/op
Client.existUser:existUser·p0.90      sample          2.175           ms/op
Client.existUser:existUser·p0.95      sample          2.327           ms/op
Client.existUser:existUser·p0.99      sample          2.716           ms/op
Client.existUser:existUser·p0.999     sample         36.796           ms/op
Client.existUser:existUser·p0.9999    sample         39.482           ms/op
Client.existUser:existUser·p1.00      sample         39.649           ms/op
Client.getUser                        sample  10078   3.169 ± 0.023   ms/op
Client.getUser:getUser·p0.00          sample          0.454           ms/op
Client.getUser:getUser·p0.50          sample          3.170           ms/op
Client.getUser:getUser·p0.90          sample          3.891           ms/op
Client.getUser:getUser·p0.95          sample          4.194           ms/op
Client.getUser:getUser·p0.99          sample          5.288           ms/op
Client.getUser:getUser·p0.999         sample          7.922           ms/op
Client.getUser:getUser·p0.9999        sample          8.028           ms/op
Client.getUser:getUser·p1.00          sample          8.028           ms/op
Client.listUser                       sample   3981   8.027 ± 0.116   ms/op
Client.listUser:listUser·p0.00        sample          2.449           ms/op
Client.listUser:listUser·p0.50        sample          7.766           ms/op
Client.listUser:listUser·p0.90        sample         10.581           ms/op
Client.listUser:listUser·p0.95        sample         11.813           ms/op
Client.listUser:listUser·p0.99        sample         15.925           ms/op
Client.listUser:listUser·p0.999       sample         23.635           ms/op
Client.listUser:listUser·p0.9999      sample         24.412           ms/op
Client.listUser:listUser·p1.00        sample         24.412           ms/op
