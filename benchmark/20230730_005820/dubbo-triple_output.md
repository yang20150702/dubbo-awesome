# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.683 ops/ms
# Warmup Iteration   2: 7.122 ops/ms
# Warmup Iteration   3: 9.076 ops/ms
Iteration   1: 9.683 ops/ms
Iteration   2: 9.724 ops/ms
Iteration   3: 10.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.902 ±(99.9%) 6.271 ops/ms [Average]
  (min, avg, max) = (9.683, 9.902, 10.298), stdev = 0.344
  CI (99.9%): [3.630, 16.173] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.652 ops/ms
# Warmup Iteration   2: 9.135 ops/ms
# Warmup Iteration   3: 9.803 ops/ms
Iteration   1: 10.080 ops/ms
Iteration   2: 10.324 ops/ms
Iteration   3: 10.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.267 ±(99.9%) 3.024 ops/ms [Average]
  (min, avg, max) = (10.080, 10.267, 10.396), stdev = 0.166
  CI (99.9%): [7.243, 13.290] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.699 ops/ms
# Warmup Iteration   2: 9.479 ops/ms
# Warmup Iteration   3: 9.954 ops/ms
Iteration   1: 9.917 ops/ms
Iteration   2: 9.892 ops/ms
Iteration   3: 9.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.866 ±(99.9%) 1.214 ops/ms [Average]
  (min, avg, max) = (9.791, 9.866, 9.917), stdev = 0.067
  CI (99.9%): [8.653, 11.080] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.277 ops/ms
# Warmup Iteration   2: 7.753 ops/ms
# Warmup Iteration   3: 8.556 ops/ms
Iteration   1: 8.484 ops/ms
Iteration   2: 8.520 ops/ms
Iteration   3: 8.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.489 ±(99.9%) 0.505 ops/ms [Average]
  (min, avg, max) = (8.465, 8.489, 8.520), stdev = 0.028
  CI (99.9%): [7.984, 8.995] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.094 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.617 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.382 ±(99.9%) 0.003 ms/op
Iteration   1: 3.201 ±(99.9%) 0.001 ms/op
Iteration   2: 3.073 ±(99.9%) 0.006 ms/op
Iteration   3: 3.132 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.135 ±(99.9%) 1.168 ms/op [Average]
  (min, avg, max) = (3.073, 3.135, 3.201), stdev = 0.064
  CI (99.9%): [1.967, 4.303] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.804 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.367 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.002 ms/op
Iteration   1: 3.148 ±(99.9%) 0.008 ms/op
Iteration   2: 3.105 ±(99.9%) 0.009 ms/op
Iteration   3: 3.232 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.162 ±(99.9%) 1.174 ms/op [Average]
  (min, avg, max) = (3.105, 3.162, 3.232), stdev = 0.064
  CI (99.9%): [1.988, 4.335] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.310 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.416 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.002 ms/op
Iteration   1: 3.324 ±(99.9%) 0.008 ms/op
Iteration   2: 3.349 ±(99.9%) 0.007 ms/op
Iteration   3: 3.275 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.316 ±(99.9%) 0.686 ms/op [Average]
  (min, avg, max) = (3.275, 3.316, 3.349), stdev = 0.038
  CI (99.9%): [2.630, 4.002] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.061 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.128 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.006 ms/op
Iteration   1: 3.918 ±(99.9%) 0.006 ms/op
Iteration   2: 3.918 ±(99.9%) 0.005 ms/op
Iteration   3: 3.745 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.860 ±(99.9%) 1.824 ms/op [Average]
  (min, avg, max) = (3.745, 3.860, 3.918), stdev = 0.100
  CI (99.9%): [2.036, 5.684] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 8.807 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.916 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.008 ms/op
Iteration   1: 3.298 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.440 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  12.533 ms/op
                 createUser·p0.9999: 19.726 ms/op
                 createUser·p1.00:   20.513 ms/op

Iteration   2: 3.158 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.178 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.367 ms/op
                 createUser·p0.95:   3.592 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  19.595 ms/op
                 createUser·p0.9999: 31.801 ms/op
                 createUser·p1.00:   31.883 ms/op

Iteration   3: 3.234 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.001 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  12.938 ms/op
                 createUser·p0.9999: 18.714 ms/op
                 createUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297163
  mean =      3.229 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17616 
    [ 2.500,  5.000) = 275194 
    [ 5.000,  7.500) = 3445 
    [ 7.500, 10.000) = 453 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 151 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.001 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     16.548 ms/op
     p(99.9900) =     30.704 ms/op
     p(99.9990) =     31.850 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.671 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.502 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.181 ±(99.9%) 0.007 ms/op
Iteration   1: 3.042 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.397 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  9.978 ms/op
                 existUser·p0.9999: 19.956 ms/op
                 existUser·p1.00:   21.561 ms/op

Iteration   2: 3.061 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.446 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.975 ms/op
                 existUser·p0.999:  11.428 ms/op
                 existUser·p0.9999: 23.396 ms/op
                 existUser·p1.00:   24.347 ms/op

Iteration   3: 3.115 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  18.055 ms/op
                 existUser·p0.9999: 74.547 ms/op
                 existUser·p1.00:   76.153 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312014
  mean =      3.073 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 308604 
    [ 5.000, 10.000) = 2983 
    [10.000, 15.000) = 123 
    [15.000, 20.000) = 132 
    [20.000, 25.000) = 138 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 10 
    [55.000, 60.000) = 3 
    [60.000, 65.000) = 1 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.510 ms/op
     p(99.0000) =      5.192 ms/op
     p(99.9000) =     12.386 ms/op
     p(99.9900) =     50.578 ms/op
     p(99.9990) =     75.875 ms/op
     p(99.9999) =     76.153 ms/op
    p(100.0000) =     76.153 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.865 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.459 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.010 ms/op
Iteration   1: 3.402 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.281 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  18.679 ms/op
                 getUser·p0.9999: 21.909 ms/op
                 getUser·p1.00:   23.396 ms/op

Iteration   2: 3.367 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.706 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   5.464 ms/op
                 getUser·p0.999:  19.396 ms/op
                 getUser·p0.9999: 22.757 ms/op
                 getUser·p1.00:   24.510 ms/op

Iteration   3: 3.168 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   5.620 ms/op
                 getUser·p0.999:  10.240 ms/op
                 getUser·p0.9999: 22.086 ms/op
                 getUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289891
  mean =      3.309 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12760 
    [ 2.500,  5.000) = 269540 
    [ 5.000,  7.500) = 6692 
    [ 7.500, 10.000) = 515 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 176 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.281 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     15.444 ms/op
     p(99.9900) =     22.282 ms/op
     p(99.9990) =     23.725 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.796 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.079 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.013 ms/op
Iteration   1: 3.856 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.790 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.496 ms/op
                 listUser·p0.999:  16.944 ms/op
                 listUser·p0.9999: 25.554 ms/op
                 listUser·p1.00:   26.477 ms/op

Iteration   2: 3.803 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  13.826 ms/op
                 listUser·p0.9999: 16.171 ms/op
                 listUser·p1.00:   16.220 ms/op

Iteration   3: 3.779 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.507 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  15.034 ms/op
                 listUser·p0.9999: 16.466 ms/op
                 listUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251611
  mean =      3.812 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 243720 
    [ 5.000,  7.500) = 5628 
    [ 7.500, 10.000) = 1538 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 252 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.790 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     14.490 ms/op
     p(99.9900) =     23.551 ms/op
     p(99.9990) =     26.051 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.902 ± 6.271  ops/ms
ClientPb.existUser                       thrpt       3  10.267 ± 3.024  ops/ms
ClientPb.getUser                         thrpt       3   9.866 ± 1.214  ops/ms
ClientPb.listUser                        thrpt       3   8.489 ± 0.505  ops/ms
ClientPb.createUser                       avgt       3   3.135 ± 1.168   ms/op
ClientPb.existUser                        avgt       3   3.162 ± 1.174   ms/op
ClientPb.getUser                          avgt       3   3.316 ± 0.686   ms/op
ClientPb.listUser                         avgt       3   3.860 ± 1.824   ms/op
ClientPb.createUser                     sample  297163   3.229 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.001           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.600           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.530           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.548           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.704           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.883           ms/op
ClientPb.existUser                      sample  312014   3.073 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.202           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.338           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.510           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.192           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.386           ms/op
ClientPb.existUser:existUser·p0.9999    sample          50.578           ms/op
ClientPb.existUser:existUser·p1.00      sample          76.153           ms/op
ClientPb.getUser                        sample  289891   3.309 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.281           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.141           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.890           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.444           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.282           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.510           ms/op
ClientPb.listUser                       sample  251611   3.812 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.790           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.686           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.258           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.490           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.551           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.477           ms/op
