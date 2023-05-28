# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.694 ops/ms
# Warmup Iteration   2: 3.832 ops/ms
# Warmup Iteration   3: 7.217 ops/ms
Iteration   1: 7.849 ops/ms
Iteration   2: 8.188 ops/ms
Iteration   3: 8.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.046 ±(99.9%) 3.216 ops/ms [Average]
  (min, avg, max) = (7.849, 8.046, 8.188), stdev = 0.176
  CI (99.9%): [4.830, 11.263] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.093 ops/ms
# Warmup Iteration   2: 6.408 ops/ms
# Warmup Iteration   3: 8.073 ops/ms
Iteration   1: 8.486 ops/ms
Iteration   2: 7.989 ops/ms
Iteration   3: 8.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.283 ±(99.9%) 4.757 ops/ms [Average]
  (min, avg, max) = (7.989, 8.283, 8.486), stdev = 0.261
  CI (99.9%): [3.526, 13.040] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.217 ops/ms
# Warmup Iteration   2: 6.719 ops/ms
# Warmup Iteration   3: 7.914 ops/ms
Iteration   1: 8.463 ops/ms
Iteration   2: 8.382 ops/ms
Iteration   3: 8.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.319 ±(99.9%) 3.358 ops/ms [Average]
  (min, avg, max) = (8.112, 8.319, 8.463), stdev = 0.184
  CI (99.9%): [4.961, 11.677] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.389 ops/ms
# Warmup Iteration   2: 5.330 ops/ms
# Warmup Iteration   3: 6.787 ops/ms
Iteration   1: 6.694 ops/ms
Iteration   2: 6.747 ops/ms
Iteration   3: 6.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.794 ±(99.9%) 2.365 ops/ms [Average]
  (min, avg, max) = (6.694, 6.794, 6.940), stdev = 0.130
  CI (99.9%): [4.428, 9.159] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 12.887 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.585 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.167 ±(99.9%) 0.007 ms/op
Iteration   1: 3.919 ±(99.9%) 0.004 ms/op
Iteration   2: 3.916 ±(99.9%) 0.005 ms/op
Iteration   3: 3.781 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.872 ±(99.9%) 1.445 ms/op [Average]
  (min, avg, max) = (3.781, 3.872, 3.919), stdev = 0.079
  CI (99.9%): [2.427, 5.317] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.584 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.095 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.760 ±(99.9%) 0.011 ms/op
Iteration   1: 3.797 ±(99.9%) 0.004 ms/op
Iteration   2: 3.784 ±(99.9%) 0.004 ms/op
Iteration   3: 3.966 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.849 ±(99.9%) 1.860 ms/op [Average]
  (min, avg, max) = (3.784, 3.849, 3.966), stdev = 0.102
  CI (99.9%): [1.989, 5.709] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 12.385 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.726 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.182 ±(99.9%) 0.004 ms/op
Iteration   1: 4.005 ±(99.9%) 0.009 ms/op
Iteration   2: 4.011 ±(99.9%) 0.005 ms/op
Iteration   3: 3.981 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.999 ±(99.9%) 0.289 ms/op [Average]
  (min, avg, max) = (3.981, 3.999, 4.011), stdev = 0.016
  CI (99.9%): [3.710, 4.288] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 13.631 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.575 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.848 ±(99.9%) 0.006 ms/op
Iteration   1: 4.684 ±(99.9%) 0.011 ms/op
Iteration   2: 4.662 ±(99.9%) 0.011 ms/op
Iteration   3: 4.537 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.627 ±(99.9%) 1.450 ms/op [Average]
  (min, avg, max) = (4.537, 4.627, 4.684), stdev = 0.079
  CI (99.9%): [3.178, 6.077] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 13.701 ±(99.9%) 0.224 ms/op
# Warmup Iteration   2: 5.349 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.235 ±(99.9%) 0.016 ms/op
Iteration   1: 4.005 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.106 ms/op
                 createUser·p0.50:   3.891 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   5.587 ms/op
                 createUser·p0.99:   7.160 ms/op
                 createUser·p0.999:  23.537 ms/op
                 createUser·p0.9999: 28.049 ms/op
                 createUser·p1.00:   28.508 ms/op

Iteration   2: 3.970 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.888 ms/op
                 createUser·p0.50:   3.756 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   6.947 ms/op
                 createUser·p0.999:  10.961 ms/op
                 createUser·p0.9999: 29.289 ms/op
                 createUser·p1.00:   30.048 ms/op

Iteration   3: 4.119 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.251 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.817 ms/op
                 createUser·p0.95:   5.710 ms/op
                 createUser·p0.99:   7.741 ms/op
                 createUser·p0.999:  27.722 ms/op
                 createUser·p0.9999: 32.227 ms/op
                 createUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237965
  mean =      4.030 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 344 
    [ 2.500,  5.000) = 221685 
    [ 5.000,  7.500) = 13763 
    [ 7.500, 10.000) = 1485 
    [10.000, 12.500) = 325 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 100 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     24.249 ms/op
     p(99.9900) =     30.317 ms/op
     p(99.9990) =     33.456 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.114 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 5.189 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 3.989 ±(99.9%) 0.014 ms/op
Iteration   1: 3.854 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.538 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   7.954 ms/op
                 existUser·p0.999:  11.158 ms/op
                 existUser·p0.9999: 26.127 ms/op
                 existUser·p1.00:   27.361 ms/op

Iteration   2: 4.012 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.686 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.735 ms/op
                 existUser·p0.95:   5.751 ms/op
                 existUser·p0.99:   7.946 ms/op
                 existUser·p0.999:  24.651 ms/op
                 existUser·p0.9999: 27.101 ms/op
                 existUser·p1.00:   28.541 ms/op

Iteration   3: 3.955 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.149 ms/op
                 existUser·p0.50:   3.809 ms/op
                 existUser·p0.90:   4.735 ms/op
                 existUser·p0.95:   5.317 ms/op
                 existUser·p0.99:   6.981 ms/op
                 existUser·p0.999:  12.797 ms/op
                 existUser·p0.9999: 29.131 ms/op
                 existUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 243750
  mean =      3.939 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 513 
    [ 2.500,  5.000) = 227114 
    [ 5.000,  7.500) = 13029 
    [ 7.500, 10.000) = 2493 
    [10.000, 12.500) = 311 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 110 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      7.799 ms/op
     p(99.9000) =     13.967 ms/op
     p(99.9900) =     28.529 ms/op
     p(99.9990) =     29.450 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.358 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 5.123 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.168 ±(99.9%) 0.015 ms/op
Iteration   1: 4.261 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.534 ms/op
                 getUser·p0.50:   3.940 ms/op
                 getUser·p0.90:   5.112 ms/op
                 getUser·p0.95:   6.652 ms/op
                 getUser·p0.99:   9.077 ms/op
                 getUser·p0.999:  18.905 ms/op
                 getUser·p0.9999: 26.919 ms/op
                 getUser·p1.00:   27.591 ms/op

Iteration   2: 3.936 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.540 ms/op
                 getUser·p0.50:   3.777 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   4.923 ms/op
                 getUser·p0.99:   6.619 ms/op
                 getUser·p0.999:  25.772 ms/op
                 getUser·p0.9999: 28.213 ms/op
                 getUser·p1.00:   29.000 ms/op

Iteration   3: 4.117 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.901 ms/op
                 getUser·p0.50:   3.903 ms/op
                 getUser·p0.90:   4.858 ms/op
                 getUser·p0.95:   5.734 ms/op
                 getUser·p0.99:   7.848 ms/op
                 getUser·p0.999:  12.370 ms/op
                 getUser·p0.9999: 30.187 ms/op
                 getUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 234005
  mean =      4.100 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 92 
    [ 2.500,  5.000) = 214533 
    [ 5.000,  7.500) = 15531 
    [ 7.500, 10.000) = 3032 
    [10.000, 12.500) = 420 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.534 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      8.176 ms/op
     p(99.9000) =     18.972 ms/op
     p(99.9900) =     29.688 ms/op
     p(99.9990) =     30.638 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.496 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 5.132 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.761 ±(99.9%) 0.018 ms/op
Iteration   1: 4.640 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.583 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.160 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  23.956 ms/op
                 listUser·p0.9999: 26.873 ms/op
                 listUser·p1.00:   27.853 ms/op

Iteration   2: 4.751 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.046 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.538 ms/op
                 listUser·p0.95:   6.365 ms/op
                 listUser·p0.99:   8.995 ms/op
                 listUser·p0.999:  21.092 ms/op
                 listUser·p0.9999: 25.660 ms/op
                 listUser·p1.00:   26.608 ms/op

Iteration   3: 4.944 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.548 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.702 ms/op
                 listUser·p0.95:   7.332 ms/op
                 listUser·p0.99:   9.896 ms/op
                 listUser·p0.999:  18.983 ms/op
                 listUser·p0.9999: 28.119 ms/op
                 listUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200923
  mean =      4.775 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 156945 
    [ 5.000,  7.500) = 37572 
    [ 7.500, 10.000) = 4995 
    [10.000, 12.500) = 678 
    [12.500, 15.000) = 202 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      1.548 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.521 ms/op
     p(95.0000) =      6.603 ms/op
     p(99.0000) =      9.404 ms/op
     p(99.9000) =     21.266 ms/op
     p(99.9900) =     26.834 ms/op
     p(99.9990) =     29.393 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.046 ± 3.216  ops/ms
ClientPb.existUser                       thrpt       3   8.283 ± 4.757  ops/ms
ClientPb.getUser                         thrpt       3   8.319 ± 3.358  ops/ms
ClientPb.listUser                        thrpt       3   6.794 ± 2.365  ops/ms
ClientPb.createUser                       avgt       3   3.872 ± 1.445   ms/op
ClientPb.existUser                        avgt       3   3.849 ± 1.860   ms/op
ClientPb.getUser                          avgt       3   3.999 ± 0.289   ms/op
ClientPb.listUser                         avgt       3   4.627 ± 1.450   ms/op
ClientPb.createUser                     sample  237965   4.030 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.106           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.669           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.399           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.348           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.249           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.317           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.521           ms/op
ClientPb.existUser                      sample  243750   3.939 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.149           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.588           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.390           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.799           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.967           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.529           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.081           ms/op
ClientPb.getUser                        sample  234005   4.100 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.534           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.792           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.677           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.176           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.972           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.688           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.588           ms/op
ClientPb.listUser                       sample  200923   4.775 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.548           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.603           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.404           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.266           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.834           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.590           ms/op
