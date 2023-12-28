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
# Warmup Iteration   1: 2.361 ops/ms
Iteration   1: 5.836 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.836 ops/ms


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
# Warmup Iteration   1: 6.045 ops/ms
Iteration   1: 13.537 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.537 ops/ms


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
# Warmup Iteration   1: 4.458 ops/ms
Iteration   1: 9.225 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.225 ops/ms


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
# Warmup Iteration   1: 2.107 ops/ms
Iteration   1: 3.353 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.353 ops/ms


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
# Warmup Iteration   1: 5.277 ±(99.9%) 0.060 ms/op
Iteration   1: 3.153 ±(99.9%) 0.038 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.153 ms/op


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
# Warmup Iteration   1: 3.560 ±(99.9%) 0.039 ms/op
Iteration   1: 1.816 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.816 ms/op


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
# Warmup Iteration   1: 4.617 ±(99.9%) 0.054 ms/op
Iteration   1: 3.447 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.447 ms/op


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
# Warmup Iteration   1: 12.260 ±(99.9%) 0.188 ms/op
Iteration   1: 8.236 ±(99.9%) 0.075 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.236 ms/op


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
# Warmup Iteration   1: 4.895 ±(99.9%) 0.099 ms/op
Iteration   1: 2.824 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   1.047 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   6.849 ms/op
                 createUser·p0.999:  13.659 ms/op
                 createUser·p0.9999: 15.667 ms/op
                 createUser·p1.00:   15.679 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11303
  mean =      2.824 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 14 
    [ 1.250,  2.500) = 4565 
    [ 2.500,  3.750) = 5541 
    [ 3.750,  5.000) = 951 
    [ 5.000,  6.250) = 102 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.047 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     13.659 ms/op
     p(99.9900) =     15.667 ms/op
     p(99.9990) =     15.679 ms/op
     p(99.9999) =     15.679 ms/op
    p(100.0000) =     15.679 ms/op


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
# Warmup Iteration   1: 3.204 ±(99.9%) 0.068 ms/op
Iteration   1: 1.958 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.476 ms/op
                 existUser·p0.50:   1.876 ms/op
                 existUser·p0.90:   2.396 ms/op
                 existUser·p0.95:   2.621 ms/op
                 existUser·p0.99:   3.276 ms/op
                 existUser·p0.999:  20.775 ms/op
                 existUser·p0.9999: 20.981 ms/op
                 existUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16330
  mean =      1.958 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15115 
    [ 2.500,  5.000) = 1151 
    [ 5.000,  7.500) = 32 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.476 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      3.276 ms/op
     p(99.9000) =     20.775 ms/op
     p(99.9900) =     20.981 ms/op
     p(99.9990) =     21.168 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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
# Warmup Iteration   1: 4.260 ±(99.9%) 0.096 ms/op
Iteration   1: 3.042 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.568 ms/op
                 getUser·p0.50:   2.916 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   5.735 ms/op
                 getUser·p0.999:  6.799 ms/op
                 getUser·p0.9999: 7.973 ms/op
                 getUser·p1.00:   8.012 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10497
  mean =      3.042 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 49 
    [1.500, 2.000) = 332 
    [2.000, 2.500) = 2543 
    [2.500, 3.000) = 2628 
    [3.000, 3.500) = 2431 
    [3.500, 4.000) = 1470 
    [4.000, 4.500) = 587 
    [4.500, 5.000) = 215 
    [5.000, 5.500) = 113 
    [5.500, 6.000) = 51 
    [6.000, 6.500) = 39 
    [6.500, 7.000) = 32 
    [7.000, 7.500) = 5 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.735 ms/op
     p(99.9000) =      6.799 ms/op
     p(99.9900) =      7.973 ms/op
     p(99.9990) =      8.012 ms/op
     p(99.9999) =      8.012 ms/op
    p(100.0000) =      8.012 ms/op


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
# Warmup Iteration   1: 12.843 ±(99.9%) 0.449 ms/op
Iteration   1: 8.002 ±(99.9%) 0.097 ms/op
                 listUser·p0.00:   1.626 ms/op
                 listUser·p0.50:   7.791 ms/op
                 listUser·p0.90:   10.240 ms/op
                 listUser·p0.95:   11.223 ms/op
                 listUser·p0.99:   13.742 ms/op
                 listUser·p0.999:  18.993 ms/op
                 listUser·p0.9999: 28.312 ms/op
                 listUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4104
  mean =      8.002 ±(99.9%) 0.097 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 126 
    [ 5.000,  7.500) = 1625 
    [ 7.500, 10.000) = 1852 
    [10.000, 12.500) = 411 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.626 ms/op
     p(50.0000) =      7.791 ms/op
     p(90.0000) =     10.240 ms/op
     p(95.0000) =     11.223 ms/op
     p(99.0000) =     13.742 ms/op
     p(99.9000) =     18.993 ms/op
     p(99.9900) =     28.312 ms/op
     p(99.9990) =     28.312 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.836          ops/ms
Client.existUser                       thrpt         13.537          ops/ms
Client.getUser                         thrpt          9.225          ops/ms
Client.listUser                        thrpt          3.353          ops/ms
Client.createUser                       avgt          3.153           ms/op
Client.existUser                        avgt          1.816           ms/op
Client.getUser                          avgt          3.447           ms/op
Client.listUser                         avgt          8.236           ms/op
Client.createUser                     sample  11303   2.824 ± 0.033   ms/op
Client.createUser:createUser·p0.00    sample          1.047           ms/op
Client.createUser:createUser·p0.50    sample          2.568           ms/op
Client.createUser:createUser·p0.90    sample          3.854           ms/op
Client.createUser:createUser·p0.95    sample          4.243           ms/op
Client.createUser:createUser·p0.99    sample          6.849           ms/op
Client.createUser:createUser·p0.999   sample         13.659           ms/op
Client.createUser:createUser·p0.9999  sample         15.667           ms/op
Client.createUser:createUser·p1.00    sample         15.679           ms/op
Client.existUser                      sample  16330   1.958 ± 0.024   ms/op
Client.existUser:existUser·p0.00      sample          0.476           ms/op
Client.existUser:existUser·p0.50      sample          1.876           ms/op
Client.existUser:existUser·p0.90      sample          2.396           ms/op
Client.existUser:existUser·p0.95      sample          2.621           ms/op
Client.existUser:existUser·p0.99      sample          3.276           ms/op
Client.existUser:existUser·p0.999     sample         20.775           ms/op
Client.existUser:existUser·p0.9999    sample         20.981           ms/op
Client.existUser:existUser·p1.00      sample         21.168           ms/op
Client.getUser                        sample  10497   3.042 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          0.568           ms/op
Client.getUser:getUser·p0.50          sample          2.916           ms/op
Client.getUser:getUser·p0.90          sample          3.994           ms/op
Client.getUser:getUser·p0.95          sample          4.399           ms/op
Client.getUser:getUser·p0.99          sample          5.735           ms/op
Client.getUser:getUser·p0.999         sample          6.799           ms/op
Client.getUser:getUser·p0.9999        sample          7.973           ms/op
Client.getUser:getUser·p1.00          sample          8.012           ms/op
Client.listUser                       sample   4104   8.002 ± 0.097   ms/op
Client.listUser:listUser·p0.00        sample          1.626           ms/op
Client.listUser:listUser·p0.50        sample          7.791           ms/op
Client.listUser:listUser·p0.90        sample         10.240           ms/op
Client.listUser:listUser·p0.95        sample         11.223           ms/op
Client.listUser:listUser·p0.99        sample         13.742           ms/op
Client.listUser:listUser·p0.999       sample         18.993           ms/op
Client.listUser:listUser·p0.9999      sample         28.312           ms/op
Client.listUser:listUser·p1.00        sample         28.312           ms/op
